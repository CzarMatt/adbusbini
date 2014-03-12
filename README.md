adbusbini
=========

Drop this into ~/.android/



Note:

All known Android vendor ids
By default ‘adb’ is compiled to consider at most 128 vendor IDs (VENDOR_COUNT_MAX), 
including the ~30-40 built-in vendors.

This means that only the first ~90 vendor entries in adb_usb.ini will be visible, 
and the rest ~3000 will be ignored.

To remedy, either make sure your desired vendor IDs appear at the top, or recompile 
‘adb’ with the limit increased to e.g. 4096.
