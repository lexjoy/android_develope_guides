# UsbInterface

see also: [UsbEndpoint](UsbEndpoint.md)

USB devices can have one or more interfaces, each one providing a different piece of functionality, separate from the other interfaces.
An interface will have one or more **UsbEndpoint**s, which are the channels by which the host transfers data with the device.

# Infos

base info:

    int clazz    = usbInterface.getInterfaceClass   ();
    int subclazz = usbInterface.getInterfaceSubclass();
    int id       = usbInterface.getId               ();
    int protocol = usbInterface.getInterfaceProtocol();
    

endpoint:

    int endpointCount = usbInterface.getEndpointCount();
    UsbEndpoint endpoint = usbInterface.getEndpoint(index);