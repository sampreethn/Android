# Install Kali NetHunter On Your Android Device
## What is Kali?

Kali Linux is a Debian-derived Linux distribution that is maintained by
Offensive Security. It was developed by Mati Aharoni and Devon Kearns. Kali
Linux is a specially designed OS for network analysts, Penetration testers, or
in simple words, it is for those who work under the umbrella of cybersecurity
and analysis.

## Kali on android!

Exploring and working with Kali Linux is great but having it on your android
device is exuberating. We can achieve this by following the steps below

## My device

I have used a OnePlus 7 GM-1901 256 GB storage 8 GB RAM mobile phone with a
Snapdragon 855 Octa-core processor. This ran android 12 earlier.
Why OnePlus 7?

1. It was on the Nethunter recommended hardware list` 
2. It was easily available.` 
3. I already had an OnePlus 7 and was happy with the service and assistance. My device bricked once and i went to the oneplus service center to get it fixed and they fixed the software for free.
4. It was one of the affordable phones in the pre used market.
5. The device firmware was provided by OnePlus Community.
## How to install NetHunter on your android device
**Important Repository**
**Note:** You got to get the versions of the rom right dont ever mess this up here are some of the softwares that i used which may be of help to you.
1) Roms (Links)
2) Magisk to root your device
3) OnePlus Local Update for Android :- To downgrade
4) TWRP custom bootloader
5) msmdownload (to recover from bricking issues)
6) Nethunter

Summary of steps
1. OEM unlock the boot loader If you are on Android12 downgrade to 11
2. Root the device
3. Install Nethunter


## Detailed Steps below

1. [Downgrade your android device to android 11 or lesser. (This step is to be followed only if you have a phone with android version 12 or above In my case I had an android 12 running device and had to downgrade it to android 10.)](https://dev.to/sampreeth/downgrade-your-android-device-to-android-10-o6c)
2. [Root your android device](https://dev.to/sampreeth/root-your-android-device-10nn). 
3. Install Kali NetHunter. 
<img width="619" height="311" alt="Screenshot from 2026-09-08 21-05-40" src="https://github.com/user-attachments/assets/9192b1ed-904d-474d-80c1-4ef87ab57e07" />

In this post you will be successfully be able to perform the third
step(installing kali nethunter)

1. Visit store.nethunter.com and download the apk
<img width="538" height="1108" alt="Screenshot from 2026-09-08 21-05-48" src="https://github.com/user-attachments/assets/6795fef2-3cec-4bf6-b7e7-40405086556d" />

2. Head to "Downloads" in your local storage and click on NetHunterStore.apk
<img width="538" height="1108" alt="Screenshot from 2026-09-08 21-05-55" src="https://github.com/user-attachments/assets/30ddd40c-0655-409e-b588-5b4db052ad72" />

3. You will get a popup asking you to confirm installation of applications from unknown sources. Click on "ok".

4. Go to NetHunter store and search for NetHunter. 
<img width="609" height="1150" alt="Screenshot from 2026-09-08 21-06-22" src="https://github.com/user-attachments/assets/dc6c5131-5489-4400-803e-4c6d13efe48d" />

5. Download and Install : 
- NetHunter Terminal Kali Linux 
- NetHunter KeX bVNC customized for NetHunter KeX
- NetHunter NetHunter installer, updater,
- interface for Kali Linux on Android.


6. Open NetHunter Terminal and type the following commands:` 

```
pkg install tsu
apt install wget
wget -o install-nethunter-termux https://offs.ec/2MceZWr
sudo apt install nethunter
nethunter
nethunter kex passwd 
nethunter kex 
``` 
1. Remember the port number eg 5901
<img width="706" height="326" alt="Screenshot from 2026-09-08 21-06-30" src="https://github.com/user-attachments/assets/dcafff0c-67fb-467f-a329-62bf0aeb91c2" />

2. Open NetHunter Kex application that we installed from the NetHunter store earlier and enter the password given to kex earlier under the VNC password textbox.
<img width="515" height="1146" alt="Screenshot from 2026-09-08 21-06-37" src="https://github.com/user-attachments/assets/17146a77-9c14-4962-be11-f1b722b323cb" />
3. After entering the password click on open VNC .
<img width="525" height="1142" alt="Screenshot from 2026-09-08 21-06-49" src="https://github.com/user-attachments/assets/205f87f3-14d8-4ff2-bf36-d1261745949e" />
4. Enjoy your Kali android.
<img width="731" height="332" alt="Screenshot from 2026-09-08 21-06-56" src="https://github.com/user-attachments/assets/4ff6ba2e-2c51-46ae-982d-a2e5e158afdb" />

