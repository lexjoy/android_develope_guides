# UsbEndpoint

see also: [UsbConstants](UsbConstants.md)

Endpoints are the channels for sending and receiving data over USB. Typically bulk endpoints are used for sending non-trivial amounts of data. Interrupt endpoints are used for sending small amounts of data, typically events, separately from the main data streams. The endpoint zero is a special endpoint for control messages sent from the host to device. Isochronous endpoints are currently unsupported.

## Infos

base info:

    int type          = usbEndpoint.getType          ();
    int address       = usbEndpoint.getAddress       ();
    int attributes    = usbEndpoint.getAttributes    ();
    int direction     = usbEndpoint.getDirection     ();
    int number        = usbEndpoint.getEndpointNumber();
    int interval      = usbEndpoint.getInterval      ();
    int maxPacketSize = usbEndpoint.getMaxPacketSize ();

type:

|Constants                |Description         |
|:------------------------|:-------------------|
|USB_ENDPOINT_XFER_CONTROL|endpoint zero       |
|USB_ENDPOINT_XFER_ISOC   |isochronous endpoint|
|USB_ENDPOINT_XFER_BULK   |bulk endpoint       |
|USB_ENDPOINT_XFER_INT    |interrupt endpoint  |

direction:

|Constants  |Description   |
|:----------|:-------------|
|USB_DIR_IN |device to host|
|USB_DIR_OUT|host to device|