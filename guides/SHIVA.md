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
5. Flash R-Firmware.
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

### PixelPlusUI v3.8 to PixelPlusUI v3.9
1. Reboot to recovery.
2. Go adv. wipe :- wipe [dalvik, cache]
3. Flash PixelPlusUI v3.9.
4. Reboot system.


# Note-
• If u are on MIUI 12.5 u can just flash recovery , vbmeta and then flash ppui.
• If u are on MIUI below 12.5 then u have to flash r firmware also.
