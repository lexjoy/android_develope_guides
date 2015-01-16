# UsbConstants

class: `android.hardware.usb.UsbConstants`

API level: `API 12`

## Class

prefix: `USB_CLASS_`

|Name               |Value|Hex Value |Description                                               |
|:------------------|----:|---------:|:---------------------------------------------------------|
|PER_INTERFACE      |    0|0x00000000|class determined on a per-interface basis.                |
|AUDIO              |    1|0x00000001|audio devices.                                            |
|COMM               |    2|0x00000002|communication devices.                                    |
|HID                |    3|0x00000003|human interface devices (for example, mice and keyboards).|
|PHYSICAL           |    5|0x00000005|physical devices.                                         |
|STILL_IMAGE        |    6|0x00000006|still image devices (digital cameras).                    |
|PRINTER            |    7|0x00000007|printers.                                                 |
|MASS_STORAGE       |    8|0x00000008|mass storage devices.                                     |
|HUB                |    9|0x00000009|USB hubs.                                                 |
|CDC_DATA           |   10|0x0000000a|CDC devices (communications device class).                |
|CSCID              |   11|0x0000000b|content smart card devices.                               |
|CONTENT_SEC        |   13|0x0000000d|content security devices.                                 |
|VIDEO              |   14|0x0000000e|video devices.                                            |
|WIRELESS_CONTROLLER|  224|0x000000e0|wireless controller devices.                              |
|MISC               |  239|0x000000ef|wireless miscellaneous devices.                           |
|APP_SPEC           |  254|0x000000fe|Application specific USB class.                           |
|VENDOR_SPEC        |  255|0x000000ff|Vendor specific USB class.                                |

## Subclass

prefix: `USB_SUBCLASS_`

|Name       |Value|Hex Value |Description                  |
|:----------|:----|---------:|:----------------------------|
|VENDOR_SPEC|  255|0x000000ff|Vendor specific USB subclass.|

## Interface subclass

prefix: `USB_INTERFACE_SUBCLASS_`

|Name|Value|Hex Value |Description                   |
|:---|----:|---------:|:-----------------------------|
|BOOT|    1|0x00000001|Boot subclass for HID devices.|

## Endpoint

prefix: `USB_ENDPOINT_`

|Name         |Value|Hex Value |Description                                                                  |
|:------------|----:|---------:|:----------------------------------------------------------------------------|
|XFER_CONTROL |    0|0x00000000|Control endpoint type (endpoint zero)                                        |
|XFER_ISOC    |    1|0x00000001|Isochronous endpoint type (currently not supported)                          |
|XFER_BULK    |    2|0x00000002|Bulk endpoint type                                                           |
|XFER_INT     |    3|0x00000003|Interrupt endpoint type                                                      |
|XFERTYPE_MASK|    3|0x00000003|Bitmask used for extracting the UsbEndpoint type from its address field.     |
|NUMBER_MASK  |   15|0x0000000f|Bitmask used for extracting the UsbEndpoint number its address field.        |
|DIR_MASK     |  128|0x00000080|Bitmask used for extracting the UsbEndpoint direction from its address field.|

## Dir

prefix: `USB_DIR_`

|Name|Value|Hex Value |Description                                                                |
|:---|----:|---------:|:--------------------------------------------------------------------------|
|OUT |    0|0x00000000|Used to signify direction of data for a UsbEndpoint is OUT (host to device)|
|IN  |  128|0x00000080|Used to signify direction of data for a UsbEndpoint is IN (device to host) |

## Type

prefix: `USB_TYPE_`

|Name    |Value|Hex Value |Description                                                                        |
|:-------|----:|---------:|:----------------------------------------------------------------------------------|
|STANDARD|    0|0x00000000|Used to specify that an endpoint zero control request is a standard request.       |
|CLASS   |   32|0x00000020|Used to specify that an endpoint zero control request is a class specific request. |
|VENDOR  |   64|0x00000040|Used to specify that an endpoint zero control request is a vendor specific request.|
|MASK    |   96|0x00000060|Bitmask used for encoding the request type for a control request on endpoint zero. |
|RESERVED|   96|0x00000060|Reserved endpoint zero control request type (currently unused).                    |