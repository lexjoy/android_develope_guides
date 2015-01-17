# UsbManager

see also: [UsbAccessory](UsbAccessory.md), [UsbDevice](UsbDevice.md)

This class allows you to access the state of USB and communicate with USB devices. Currently only host mode is supported in the public API.

You can obtain an instance of this class by calling **Context.getSystemService()**.

    UsbManager manager = (UsbManager) getSystemService(Context.USB_SERVICE);

## Accessory

get instance:

    UsbAccessory[] accessorys = usbManager.getAccessoryList();

check permission:

    boolean hasPermission = usbManager.hasPermission(accesory);

request permission:

    // register
    //   ACTION_ACCESSORY_ATTACHED
    // and
    //   ACTION_ACCESSORY_DETACHED
    // intent filter broadcast after request permission.
    //
    // boradcast intent extras:
    //   EXTRA_ACCESSORY        accessory
    //   EXTRA_PERMISSION_GRANT permission grant result
    usbManager.requestPermission(accessory, pendingIntent);

open:

    FileDescriptor fileDescripter = usbManager.openAccessory(accessory);

## Device

get instance:

    Map<String, UsbDevice> deviceMap = usbManager.getDeviceList();

check permission:

    boolean hasPermission = usbManager.hasPermission(device);

request permission:

    // register
    //   ACTION_DEVICE_ATTACHED
    // and
    //   ACTION_DEVICE_DETACHED
    // intent filter broadcast after request permission.
    //
    // boradcast intent extras:
    //   EXTRA_DEVICE           device
    //   EXTRA_PERMISSION_GRANT permission grant result
    usbManager.requestPermission(device, pendingIntent);

open:

    UsbDeviceConnection deviceConnection = usbManager.openDevice(device);
