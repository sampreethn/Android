# Downgrade your android device to android 10

**Caution: This is only to unlock the oem of your mobile phone and should be done only if you have android 12 or above in your device**

## Enable Developer Options:
1. Head to settings on your device.
2. Click on about device
<img width="525" height="1163" alt="Screenshot from 2026-09-02 10-12-24" src="https://github.com/user-attachments/assets/ec2e9986-7506-4e79-a703-0d0abf1e3e77" />


3. Tap on Build number 7 times to enable developer options
<img width="530" height="1169" alt="Screenshot from 2026-09-02 10-12-33" src="https://github.com/user-attachments/assets/3e4138ba-b505-45e4-b251-81deaabeddd2" />

4. You will get a popup saying that you are a developer now.
<img width="530" height="1169" alt="Screenshot from 2026-09-02 10-12-48" src="https://github.com/user-attachments/assets/b69bd3fb-c4b2-4d61-846d-28078c02b901" />


5. Head to developer options on your phone and turn the on advanced reboot and USB debugging.

<img width="530" height="1169" alt="Screenshot from 2026-09-02 10-13-01" src="https://github.com/user-attachments/assets/9d350177-6eaa-404f-a982-3f12f81d47e6" />

6. Connect your phone to your PC with a USB cable.
7. Once you've backed up all of your data, you'll need to download an Android factory image of the version you want to go back to. You can find this at the manufacturers website if not then best  place to find it is [XDA forums](https://xdaforums.com/)
<img width="735" height="556" alt="Screenshot from 2026-09-02 10-13-13" src="https://github.com/user-attachments/assets/c83be468-1c42-46b8-b270-6395d6ec09e8" />


8. Download the SDK platform tools if you are using windows then,
   1. Extract the zip file to the desired location.
<img width="606" height="433" alt="Screenshot from 2026-09-02 10-13-23" src="https://github.com/user-attachments/assets/f4a718cd-5005-4d39-ac4c-5eb9f459f528" />

   2. Navigate to the platform tools folder and type cmd in the search text-box
<img width="742" height="373" alt="Screenshot from 2026-09-02 10-13-31" src="https://github.com/user-attachments/assets/dc2f10a6-d0fc-4e23-81d4-5c1b40bab813" />

   3. Then type
   ```
   adb devices
    ```

      in the command prompt. You will get a string with the device being connected to your pc
<img width="742" height="373" alt="Screenshot from 2026-09-02 10-37-18" src="https://github.com/user-attachments/assets/291a3033-d645-405d-b966-72da62610f2a" />

   4. Type
    ```
    adb reboot bootloader
    ```
      in the command prompt.
9.  Your device will reboot into fastboot mode. Now you learnt how to set your phone to fastboot mode.
<img width="325" height="304" alt="Screenshot from 2026-09-02 10-37-48" src="https://github.com/user-attachments/assets/5cbe92f1-a56f-422e-8a91-217f4939f9b3" />

10. Press the power button and boot your device.
11. Search for your local updater apk (for oneplus it is oplocal updater)
    **Caution: remember to do this in fastboot mode**
12. From the stock rom you downloaded, take the .img file and type the following command in the same directory
    ```
    fastboot flash bootloader [bootloader file name].img
    ```
13. Downgrade to the desired version by selecting it in the apk installer.
<img width="279" height="638" alt="Screenshot from 2026-09-02 10-38-06" src="https://github.com/user-attachments/assets/8f0160ce-4239-4795-a712-f111b44fb727" />

Now you are good to go your mobile phone will be downgraded to the one you like.
