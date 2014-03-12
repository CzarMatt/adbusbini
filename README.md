adbusbini
=========
This file contains every known Android vendor id.

Drop this into ~/.android/



Note:

By default adb is compiled to consider at most 128 vendor IDs (VENDOR_COUNT_MAX), 
including the built-in vendors.

This means that only the first ~90 vendor entries in adb_usb.ini will be visible, 
and the rest will be ignored.

Either make sure your desired vendor IDs appear at the top, or recompile 
adb with the limit increased. (example: 4096)
