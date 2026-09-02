# Downgrade your android device to android 10

**Caution: This is only to unlock the oem of your mobile phone and should be done only if you have android 12 or above in your device**
## Enable Developer Options:
1. Head to settings on your device.
2. Click on about device


3. Tap on Build number 7 times to enable developer options

4. You will get a popup saying that you are a developer now.


5. Head to developer options on your phone and turn the on advanced reboot and USB debugging.


6. Connect your phone to your PC with a USB cable.
7. Once you've backed up all of your data, you'll need to download an Android factory image of the version you want to go back to. You can find this at the manufacturers website if not then best  place to find it is XDA forums


8. Download the SDK platform tools if you are using windows then,
   1. Extract the zip file to the desired location.

   2. Navigate to the platform tools folder and type cmd in the search text-box

   3. Then type
   ```adb devices
    ```

      in the command prompt. You will get a string with the device being connected to your pc

   4. Type
    ```adb reboot bootloader
    ```
      in the command prompt.
9.  Your device will reboot into fastboot mode. Now you learnt how to set your phone to fastboot mode.
10. Press the power button and boot your device.
11. Search for your local updater apk (for oneplus it is oplocal updater)
    **Caution: remember to do this in fastboot mode**
12. From the stock rom you downloaded, take the .img file and type the following command in the same directory
    ```fastboot flash bootloader [bootloader file name].img
    ```
13. Downgrade to the desired version by selecting it in the apk installer.
Now you are good to go your mobile phone will be downgraded to the one you like.
