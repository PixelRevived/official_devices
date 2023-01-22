# Clean flash (coming from a different ROM):
- Download ROM from the link above
- Flash PixelOS recovery via adb
- Go to recovery
- Go to format section and wipe data,cache and system
- Go to Apply Update where u will have two ways to flash the rom-
- ADB Sideload -
Copy rom zip In adb folder and copy file name of the rom zip , select adb option in recovery on phone and then on pc type
==adb sideload romfilename.zip==
- SD CARD - If u want to flash file from sd card just select sd card and navigate to rom file and Install it
- Flash VBmeta_disabler.zip
- Reboot and voila!
- To get root access, reboot to recovery after ROM setup and flash magisk.

# Updating to a newer build (dirty flash):
- Flash ROM zip and magisk (optional)
- Reboot and voila!
- If rom loops to recovery, flash VBmeta_disabler.zip and reboot
