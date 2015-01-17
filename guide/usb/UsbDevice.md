# UsbDevice

see also: [UsbInterface](UsbInterface.md), [UsbDeviceConnection](UsbDeviceConnection.md), [UsbRequest](UsbRequest.md)

To communicate with the device, you open a **UsbDeviceConnection** for the device and use **UsbRequest** to send and receive data on an endpoint. **controlTransfer(int, int, int, int, byte[], int, int)** is used for control requests on endpoint zero.

## Infos

base info:

    int    clazz     = usbDevice.getDeviceClass   ();
    int    subclazz  = usbDevice.getDeviceSubclass();
    int    id        = usbDevice.getDeviceId      ();
    int    vendorId  = usbDevice.getVendorId      ();
    int    productId = usbDevice.getProductId     ();
    int    protocol  = usbDevice.getDeviceProtocol();
    String name      = usbDevice.getDeviceName    ();

interface:

    int interfaceCount = usbDevice.getInterfaceCount();
    UsbInterface interface = usbDevice.getInterface(index);