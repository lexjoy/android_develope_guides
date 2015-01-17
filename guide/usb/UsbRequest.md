# UsbRequest

A class representing USB request packet. This can be used for both reading and writing data to or from a UsbDeviceConnection. UsbRequests can be used to transfer data on bulk and interrupt endpoints. Requests on bulk endpoints can be sent synchronously via bulkTransfer(UsbEndpoint, byte[], int, int) or asynchronously via queue(ByteBuffer, int) and requestWait(). Requests on interrupt endpoints are only send and received asynchronously.

Requests on endpoint zero are not supported by this class; use controlTransfer(int, int, int, int, byte[], int, int) for endpoint zero requests instead.

## Infos

base info:

    // Result
    //   normal endpoint for the request
    //   null   the request is not opened
    UsbEndpoint usbEndpoint = usbRequest.getEndpoint();

client data:

    // Returns the client data for the request.
    //
    // This can be used in conjunction with setClientData(Object)
    // to associate another object with this request,
    // which can be useful for maintaining state between calls to queue(ByteBuffer, int) and requestWait()
    Object clientData = usbRequest.getClientData();

    // Sets the client data for the request.
    //
    // This can be used in conjunction with getClientData()
    // to associate another object with this request,
    // which can be useful for maintaining state between calls to queue(ByteBuffer, int) and requestWait()
    usbRequest.setClientData(object);

## Transfer

initialize:

    // Initializes the request so it can read or write data on the given endpoint.
    // Whether the request allows reading or writing depends on the direction of the endpoint.
    boolean isInitSuccess = usbRequest.initialize(usbConnection, usbEndpoint);

queue:

    // Queues the request to send or receive data on its endpoint.
    // For OUT endpoints, the given buffer data will be sent on the endpoint.
    // For IN endpoints, the endpoint will attempt to read the given number of bytes into the specified buffer.
    // If the queueing operation is successful, we return true and the result will be returned via requestWait()
    // 
    // Params
    //   buffer the buffer containing the bytes to write, or location to store the results of a read
    //   length number of bytes to read or write
    boolean isQueueSuccess = usbRequest.queue(byteBuffer, length);

cancel:

    // cancels a pending queue operation.
    boolean isCancelSuccess = usbRequest.cancel();

close:

    // Releases all resources related to this request.
    usbRequest.close();

