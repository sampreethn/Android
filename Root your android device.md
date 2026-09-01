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

## **How To Root An Android Device?** 

1. If you are running android 12 or greater there is a possibility that you are prevented to unlock the OEM so follow the guide to downgrade your device. 

2. In order to enable developer options and OEM unlocking have a look at my other blog.. 

3. Put your device into fastboot mode 

```adb reboot bootloader ```

4. Connect your device to your pc through a usb cable and OEM unlock. 

``` fastboot oem unlock ```

<img width="368" height="607" alt="Screenshot from 2026-09-01 12-06-04" src="https://github.com/user-attachments/assets/4734d3ce-40af-422d-81bd-1829b85c274b" />

6. Press the volume down button once to select the 'yes' option and then press the power button to unlock the oem.

7. To root your device you need to follow a few steps.

7.1. Download the device firmware either from their
community or from [xda forums](https://xdaforums.com/) on your pc.

7.2. Download [Payload Dumper](https://bit.ly/3O38nbz) and
[Platform tools](https://developer.android.com/tools/releases/platform-tools) on your pc 

7.3. Extract and open the device firmware folder and copy the payload.bin file for my oneplus device it looks like this 

<img width="805" height="498" alt="Screenshot from 2026-09-01 12-06-14" src="https://github.com/user-attachments/assets/fb2f7e7d-13e7-44e0-acd1-3fbcebf77115" />



7.4. Next extract the payload dumper folder and paste the payload.bin file that we copied earlier in the payload_input folder 

7.5. Run the payload dumper application(as administrator) this step will take some time wait for the application to close itself. 

7.6. In the payload_output folder copy the boot.img file paste it to the suitable directory and type cmd and hit enter in the text-box above. 

7.7. Connect your phone to the pc through a USB cable . 

7.8. Execute the following command: 

```adb push boot.img storage/self/primary/``` 

7.9. On your phone search for magisk in your browser and 

download and install the latest version. Or install magisk code : adb install magisk-ver.apk 

7.10. Open the magisk application and click on install 

<img width="392" height="885" alt="Screenshot from 2026-09-01 12-06-25" src="https://github.com/user-attachments/assets/e8600077-a32d-4f6c-ac6a-f69fba78396b" />

7.11. Next click on select and patch a file then navigate to the boot.img file on your phone and select it.

<img width="392" height="885" alt="Screenshot from 2026-09-01 12-06-32" src="https://github.com/user-attachments/assets/97118be6-a03f-449f-b2cb-f2fe0e996bfe" />

7.12. Copy the patched file to your pc.
<img width="809" height="403" alt="Screenshot from 2026-09-01 12-06-41" src="https://github.com/user-attachments/assets/4bd97c04-9b5f-49e3-8ab9-9c5ec280cca2" />


7.13. Enter fastboot mode on your phone and type the following in your pc 

```
fastboot flash boot patchedfile.img
```

Note: Remember to replace the patchedfile.img by the file you copied to your computer. 


<img width="802" height="146" alt="Screenshot from 2026-09-01 12-06-51" src="https://github.com/user-attachments/assets/3d99709b-04d9-4a90-9ae6-2c4b64c5cd8c" />

7.14. Boot your phone by pressing the power button and 

you are good to go. 

7.15. In order to verify if you are rooted or not , 

install the rootchecker app and hit on verify 

root. 

That's it folks happy rooting, dont brick your phone. 

