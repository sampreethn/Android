# **Root your android device** 

#android11#nethunter#rooting#superuser 

## **What Is Rooting?** 

Rooting is a process of giving the device user the superuser permissions or the privilege to access the device system files 

## **Why Is It Needed ?** 

1. Rooting allows elevated system access. 

2. It enhances the engineering control over your phone. 

3. You can decide what your phone can do . 

4. The appearance of your device will be in your hands (ultimately customisable). 

5. All aspects of the operating system can be customised with the only real limitation being the level of coding expertise. 

6. Rooting also gives you access to the device's system files. 

7. It is done to remove the restrictions that the device hardware manufacturer and the carriers have put on the device 

## **How To Root An Android** 

## **Device?** 

1. If you are running android 12 or greater there is a possibility that you are prevented to unlock the OEM so follow the guide to downgrade your device. 

2. In order to enable developer options and OEM unlocking have a look at my other blog.. 

3. Put your device into fastboot mode 

   - code : adb reboot bootloader 

4. Connect your device to your pc through a usb cable and OEM 

unlock. 

code : fastboot oem unlock 

### Unlock bootloader? 

If you unlock the bootloader, you will be able to install custom operating system software on this phone. 

A custom OS is not subject to the same testing as the original OS, and can cause your phone and installed applications to stop working properly. 

To prevent unauthorized access to your personal data, unlocking the bootloader will also delete all personal data from your phone (a “factory data reset”). 

Press the Volume Up/Down buttons to select Yes or No. Then press the Power button to continue. 

Yes 

Unlock bootloader (may void warranty) 



<!-- Start of picture text -->
No<br>Do not unlock bootloader and restart phone<br><!-- End of picture text -->

7.3. Extract and open the device firmware folder and copy the payload.bin file for my oneplus device it looks like this 



7.4. Next extract the payload dumper folder and paste the payload.bin file that we copied earlier in the payload_input folder 

7.5. Run the payload dumper application(as administrator) this step will take some time wait for the application to close itself. 

7.6. In the payload_output folder copy the boot.img file paste it to the suitable directory and type cmd and hit enter in the text-box above. 

7.7. Connect your phone to the pc through a USB cable . 

7.8. Execute the following command: 

code: adb push boot.img storage/self/primary/ 

7.9. On your phone search for magisk in your browser and 

download and install the latest version. Or install magisk code : adb install magisk-ver.apk 

7.10. Open the magisk application and click on install 



<!-- Start of picture text -->
10:08 G @ A Se ull 73%e<br>Home $03<br>oNaie Magisk. ($] Install<br>Installed N/A<br>Zygisk No<br>Ramdisk Yes<br>| App [3] Install<br>Latest 27.0(27000)<br>Installed 27.0(27000)<br>Package com.topjohnwu.magisk<br>Support Us<br>Follow Us<br>@topjohnwu . ws)<br>ewb2060 YF C)<br>@yujinchengOs J a) @<br>Logs<br><!-- End of picture text -->



<!-- Start of picture text -->
11:43 @ AS fe ll 71%ow<br>= Redev_utlimatte Q.<br>Alarms Android<br>Audiobooks DCIM<br>Documents Download<br>Movies Music<br>|<br>Notifications Pictures<br>Podcasts Recordings<br>Ringtones<br>Ka Ka<br>i Wd it Wi<br>142x142.grey boot.img<br>a* Selecta raw image (*.img) or an ODIN<br>tarfile (*.tar) or a payload.bin (*.bin)<br><!-- End of picture text -->



#### 7.13. Enter fastboot mode on your phone and type the following in your pc 

```
fastboot flash boot patchedfile.img
```

Note: Remember to replace the patchedfile.img by the file you copied to your computer. 



#### 7.14. Boot your phone by pressing the power button and 

you are good to go. 

7.15. In order to verify if you are rooted or not , 

install the rootchecker app and hit on verify 

root. 

#### That's it folks happy rooting, dont brick your phone. 

