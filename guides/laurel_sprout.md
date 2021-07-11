![Installation Guide For PixelPlusUI on Xiaomi MI A3 (laurel_sprout)](https://i.imgur.com/pmZkslu.png "Installation")

# Installation Guide For PixelPlusUI on Xiaomi MI A3 (laurel_sprout)

### CLEAN FLASH GUIDE (A10FW)
Remove your lockscreen password!!
1. Go to recovery
2. Format Data -> Type yes
3. Wipe davlik, data, system
4. Flash Pixel Plus UI ROM
5. Flash recovery zip (no need to change any kind of slot)
6. Reboot system

### CLEAN FLASH GUIDE (A11FW)
1. Flash Los recovery img via fastboot
   fastboot flash boot <name of the file>
2. Reboot to recovery
3. Perform factory reset
4. Navigate Apply update -> apply from ADB
5. Sideload Pixel Plus UI ROM.zip
   adb sideload <rom zip name>
6. Reboot system

### DIRTY FLASH GUIDE
1. Reboot to Recovery
3. Flash Pixel Plus UI ROM
4. Wipe Dalvik, Cache.
5. Reboot to System

## Notes:
- Clean flash is must if coming from other roms.
- Only do dirty flash for updating pixel plus ui rom to latest version.
