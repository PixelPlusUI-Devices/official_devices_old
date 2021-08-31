![Installation Guide For PixelPlusUI on Mi 10T/PRO - Apollo/Apollopro](https://i.imgur.com/pmZkslu.png "Installation")

# Installation Guide For PixelPlusUI on Apollo/Apollopro

## IF YOU ARE MOVING FROM ANOTHER ROM, CLEAN FLASH Is COMPULSORY.

### Clean Flash 
1-Download Rom 

2-Download Recovery: [Here](https://drive.google.com/file/d/15FugLW80NUoSwzLna_GT8BeUveUOHVeo/view?usp=sharing)

3-Boot to fastboot using: adb reboot fastboot or power off and press Power button and Volume Down.

4-Flash provided recovery using: fastboot flash recovery TWRP_3.5.2_10_By_Master.img

5-Then reboot to recovery using: fastboot reboot-recovery

6-After that go to wipe and format data from recovery.

7-Reboot recovery.

8-After Rebooting in recovery, Go to Advance Option and then Select ADB sideload.

9-After then Flash ROM using:  adb sideload PixelPlusUI_3.8_apollo-11.0-20210831-0750-OFFICIAL.zip.

10-Similarly Flash firmware using: adb sideload fw_apollo_miui_apolloglobal_v12.5.2.0.rjdmixm_d573addb51_11.0.zip

11-Reboot

Note: make sure all files are present in the ADB folder.

### DIRTY FLASH
1-Download the latest build

2-Reboot to recovery

3-After booting in recovery, Go to Advance Option and then Select ADB sideload.

4-After then Flash ROM using:  adb sideload PixelPlusUI_3.8_apollo-11.0-20210831-0750-OFFICIAL.zip

5-Wipe Cache

6-Reboot

