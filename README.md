# Dell-Latitude-5480-Hackintosh-Sonoma-OpenCore-0.9.9
![macOS](https://img.shields.io/badge/macOS-Sonoma-green.svg)
![version](https://img.shields.io/badge/14.5-red)
![OpenCore](https://img.shields.io/badge/OpenCore-0.9.9-green)
![LICENSE](https://img.shields.io/badge/license-MIT-green.svg)

Provided efi is working perfectely fine and is very stable for daily use 
#
This repo contains the files necessary to install Monterey in Dell latitude 5480

Patch your systems own DSDT Accordingly

![](image/screenshot.png)

# Specification 
- <b>Model</b>: Dell Latitude 5480
- <b>CPU</b>: Intel(R) Core(TM) i5-6300U CPU @ 2.50GHz
- <b>GPU</b>: Intel HD Graphics 520
- <b>RAM</b>: 16 GB 2133MHz DDR4
- <b>Storage</b>: 256GB SATA SSD
- <b>Screen</b>: 14" (1920x1080)
- <b>Wi-Fi</b>: Intel Dual Band Wireless-AC8625
- <b>Ethernet</b>: Intel Ethernet I219-LM
- <b>Camera</b>: 720p
- <b>Touchpad</b>: Alpsalpine I2C
- <b>Battery</b>: 3-cell with inside battery 

# What's Working?
- [x] Wi-Fi & Bluetooth 
- [x] Intel HD 520 Graphics (with graphics acceleration spoofed as Intel HD 620)
- [x] HDMI port (With HDMI Audio no purple tint)
- [x] Internel Speaker
- [x] Headphone Jack
- [x] Internal camera 
- [x] Trackpad (multigestures work use tap to click option)
- [x] CPU Power Management 
- [x] All USB ports
- [x] Keyboard (all fn Keys Brightness key works)
- [x] Intel Ethernet port
- [x] iMessage, FaceTime, App Store, iTunes Store (with valid smbios)
- [x] DRM support 
- [x] Sleep / Wake (lid sleep and lid wake) 

# What's not working ⚠️
- [x] Handoff, Universal control, Airdrop (Unless you have Broadcom wifi Card)
- [x] SD Card Reader (Damaged so can't test)
- [x] Everything Else Work

# Solutions 
- [x] If your CPU usage is high try
```
$ sudo launchctl disable gui/501/com.apple.transparencyd
```
# Refrences
- [dortania Hackintosh guides](https://dortania.github.io/OpenCore-Install-Guide/)


