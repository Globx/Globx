- š Hi, Iām @Globx
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

Current Projects

[QMK nullbits SCRAMBLE 3key](https://github.com/Globx/qmk_firmware/tree/master/keyboards/nullbitsco/scramble/keymaps/3key)

[nullbits SyncData for Nibble65 w/Tidbit + TRRS](https://github.com/Globx/qmk_firmware/tree/master/keyboards/nullbitsco)
This project adds support for syncing RGB mode, RGB enabled, HSV and volume from the Tidbit to the Nibble.  Changes in Common remote_kb.h and .c, as well as using oled2 keymaps for both Nibble 65 and Tidbit.  HSV is your color setting for modes like static color.  When using the TRRS port, the Nibble 65 is the host and the Tidbit is the remote KB.  Currently there is only syncing from the Tidbit to the Nibble 65.  This is an early proof of concept build and may not represent best practices for implementing these new features.  Encoder volume controls are also passed to the host using process_record_remote_kb.

NOTE: rules.mk contains "CONSOLE_ENABLE = yes".  If console logging isn't required, then set this to no or delete this line from both Nibble and Tidbit rules.mk files.

<!---
Globx/Globx is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
