# UsbDeviceConnection

see also: [UsbRequest](UsbRequest.md)

Used for sending and receiving data and control messages to a USB device.

## Infos

base info:

    // Result
    //   normal serial number of the device
    //   null   the device has not been opened.
    String serial = usbDeviceConnection.getSerial();

fileDescriptor:

    // This is intended for passing to native code to access the device.
    //
    // Result
    //   normal native file descriptor
    //   -1     the device is not opened.
    int fileDescriptor = usbDeviceConnection.getFileDescriptor();

## Transfer

control transfer:

    // Params
    //   requestType request type for this transaction
    //   request     request id   for this transaction
    //   value       value field  for this transaction
    //   index       index field  for this transaction
    //   buffer      null if no data needs to be sent or received
    // Result
    //   0 | position -> success
    //   negative     -> failure
    int transferedDataSize = usbDeviceConnection.controlTransfer(requestType, request, value, index, buffer, length, timeout);

bulk transfer:

    // Params
    //   buffer  buffer for date to send or receive
    //   length  length for data to send or receive
    //   timeout in milliseconds
    // Result
    //   0 | position -> success
    //   negative     -> failure
    int transferedDataSize = usbDeviceConnection.bulkTransfer(endpoint, buffer, length, timeout);

close

    // once device is closed, it can not be used again.
    // the client must call openDevice(usbDevice) again to retrieve a new instance
    // to reestablish ccommunication with the device.
    usbDeviceConnection.close();

## Request

wait:

    // Waits for the result of a queue(ByteBuffer, int) operation.
    // this may return requests queued on multiple UsbEndpoints.
    //
    // When multiple endpoints are in use, getEndpoint() and getClientData()
    // can be useful in determining how to process the result of this function.
    UsbRequest usbRequest = usbDeviceConnection.requestWait();

## Exclusive access

claim access:

    // Params
    //   isClaimedForce true to disconnect kernel driver if necessary
    boolean isClaimedSuccess = usbDeviceConnection.claimInterface(usbInterface, isClaimedForce);

release access:

    boolean isReleaseSuccess = usbDeviceConnection.releaseInterface(usbInterface);
