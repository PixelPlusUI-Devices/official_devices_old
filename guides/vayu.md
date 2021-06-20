![Installation Guide For PixelPlusUI on Poco X3 Pro (vayu/bhima)](https://i.imgur.com/pmZkslu.png "Installation")

# Installation Guide For PixelPlusUI on Poco X3 Pro (vayu/bhima)

### CLEAN FLASH (RECOMMENDED)
1. Reboot to Recovery
2. Flash recommended [MIUI stock ROM](https://xiaomifirmwareupdater.com/miui/vayu/)
    - Skip if you are already on recommended stock ROM
    - Flashable ZIP or fastboot ROM will work
3. Wipe Dalvik, Data and Cache in Advanced Wipe
    - Only applies if you come from decrypted build (check step 8 for encrypted build)
4. Flash Pixel Plus UI ROM
5. Flash custom kernel (optional)
6. Flash Magisk (optional)
7. Flash [DFE](https://t.me/PocoX3ProUpdates/195) (optional)
    - Disables force encryption on custom AOSP ROMs on stock MIUI vendor
    - Format Data will not be necessary next time you have to clean flash
8. Format Data, type "yes" and press enter
    - Only applies if you come from encrypted build (check step 3 for decrypted build)
9. Reboot to System

### DIRTY FLASH
1. Reboot to Recovery
2. Wipe Dalvik and Cache in Advanced Wipe (optional)
3. Flash Pixel Plus UI ROM
4. Flash custom kernel (optional)
5. Flash Magisk (optional)
6. Flash [DFE](https://t.me/PocoX3ProUpdates/195) (optional)
    - Disables force encryption on custom AOSP ROMs on stock MIUI vendor
    - Format Data will not be necessary next time you have to clean flash
    - Make sure to flash before booting or your phone will be encrypted
7. Reboot to System

## Notes: 
- Recommended stock MIUI vendor:
    - 12.0.4.0
    - 12.0.6.0 (recommended)
    - 12.5.1.0
- [TWRP](https://t.me/PocoX3ProUpdates/259) recommended
- Clean flash if you face any bugs