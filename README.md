# Unofficial Sfxr for Raspberry Pi OS

![A screenshot of Sfxr running on Raspberry Pi OS](https://github.com/stevepdp/unofficial-sfxr-for-raspberry-pi-os/blob/master/sfxr-screenshot.png?raw=true)

[Sfxr](https://www.drpetter.se/project_sfxr.html) is a tool for generating chippy sound effects which are exportable to .wav files.

For Raspberry Pi OS (32-bit) or Raspberry Pi OS (Legacy), install the armhf package with:  

`sudo dpkg -i sfxr_1.2.1_0_armhf.deb`  

For Raspberry Pi OS (64-bit), install the arm64 package with:  

`sudo dpkg -i sfxr_1.2.1_0_arm64.deb`  

If you've forgotten which architecture you're running, this'll tell you:  

`dpkg --print-architecture`  

If the app doesn't launch, then it's likely you installed the wrong architecture. You can remove the package installation regardless with:  

`sudo dpkg -r sfxr`  
