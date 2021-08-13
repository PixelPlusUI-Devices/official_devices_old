![Installation Guide For PixelPlusUI on Shiva](https://i.imgur.com/pmZkslu.png "Installation")

# Flashing Custom Recovery using PC 
Guide to flash recovery on POCO M2.

Requirements:
• A computer
• Unlocked bootloader
• Ability to use brain

Steps:
1. Download the following files-
• [Platform Tools](https://developer.android.com/studio/releases/platform-tools)
• [Custom Recovery](https://drive.google.com/uc?id=1HYv12k7LQO8htbgTd7F8Z_JyClClct6T&export=download)
• [VBMeta.img](https://drive.google.com/uc?id=1HEuwO4_9irbzfh4TN8qE35siqYhYqmnd&export=download)
2. Copy custom recovery and vbmeta.img to platform tools.
3. Boot your phone into fastboot mode and connect it to your computer.
4. Open command prompt in platform tools directory and type the following commands-

fastboot flash recovery recoveryname.img

fastboot --disable-verification flash vbmeta vbmeta.img

fastboot reboot recovery

Done, happy flashing :)

## Installation Guide For PixelPlusUI on Shiva

### MIUI to PixelPlusUI
1. After flashing custom recovery, boot to recovery.
2. Go adv. wipe :- wipe [dalvik, cache, internal storage]
3. Format data (By typing yes)
4. Reboot to recovery.
5. Flash ported R-Firmware.
6. Reboot to recovery.
7. Flash rom.
8. Reboot system.

### A different Rom to PixelPlusUI
1. Reboot to recovery.
2. Go adv. wipe :- wipe [dalvik, cache, internal storage]
3. Format data (By typing yes)
4. Reboot to recovery.
5. Flash rom.
6. Reboot system.

### PixelPlusUI v3.7 to PixelPlusUI v3.8
1. Reboot to recovery.
2. Go adv. wipe :- wipe [dalvik, cache, internal storage]
3. Format data (By typing yes)
4. Reboot to recovery.
5. Flash ported R-Firmware.
6. Reboot to recovery.
7. Flash PixelPlusUI v3.8.
8. Reboot system.

## Note:
• U should be on [MIUI v12.0.1.0](https://bigota.d.miui.com/V12.0.1.0.QJRINXM/shiva_in_global_images_V12.0.1.0.QJRINXM_20201224.0000.00_10.0_in_3b6a5b3c4c.tgz) before flashing custom recovery.
• If u are on MIUI v12.0.3.0 or above , Downgrade to MIUI v12.0.1.0.
