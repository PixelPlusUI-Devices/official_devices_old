![Installation Guide For PixelPlusUI on Shiva](https://i.imgur.com/pmZkslu.png "Installation")

# Flashing Custom Recovery using PC 
Guide to flash recovery on Redmi 9(lancelot).

Requirements:
• A computer
• Unlocked bootloader
• Ability to use brain

Steps:
1. Download the following files-
• [Platform Tools](https://developer.android.com/studio/releases/platform-tools)
• [Custom Recovery](https://telegram.me/HelioG85_Updates/268)
• [VBMeta.img](https://telegram.me/HelioG85_Unified/198424)
2. Copy custom recovery and vbmeta.img to platform tools.
3. Boot your phone into fastboot mode and connect it to your computer.
4. Open command prompt in platform tools directory and type the following commands-

fastboot flash recovery recoveryname.img

fastboot --disable-verification flash vbmeta vbmeta.img

fastboot reboot recovery

Done, happy flashing :)

## Installation Guide For PixelPlusUI on Redmi 9 (lancelot)


### MIUI to PixelPlusUI
1. Take [IMEI-Backup](https://telegram.me/HelioG85_Unified/242714)(don't complain if you don't take backup and lose imei)(also store backup on pc or somewhere safe[IMPORTANT], As Data Will Be Formatted During Backup)
2. Flash your Device Respective FW From [here](https://telegram.me/HelioG85_Unified/248386)
3. Reboot To Recovery
4. wipe Dalvik/Art, Cache, Format Data --> yes
5. Flash rom in recovery


### A different Rom to PixelPlusUI
1. If On Any R Vendor Rom, Then Reboot to recovery, Flash PixelPlusUI, Wipe Dalvik, Art-Cache
2. If On Q Vendor Rom or Non-OSS Rom, Follow 'MIUI to PixelPlusUI'


### PixelPlusUI(OLD VERSION) to PixelPlusUI(NEW VERSION)
1. Same As MIUI to PixelPlusUI(cleanflash Mandatory Because Inital R Vendor build)
1. If ON PPUI 3.8 Or Later, Flash Rom, Wipe Dalvik/Art Cache And Cache And Reboot

## If You Face Bugs After OTA/Dirty Flash
1. Follow MIUI to PixelPlusUI
