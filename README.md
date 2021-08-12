# Hackintosh
EFI made for MSI Prestige 15 A10SC with Opencore bootloader

## System specifications:
| **Component** | **Model** |
| ------------- | --------- |
| CPU | Intel Comet Lake i7-10710u |
| RAM | 16GB (2 x 8GB) DDR4 HyperX Impact 2666MHz |
| IGPU | Intel Graphics UHD 630	|
| DGPU | Nvidia GTX1650 Max-Q |
| Display | CMN N156HCE-EN1 FHD (1080p) 60Hz |
| NVMe 1 | Samsung 970 Evo 1TB |
| Audio | Realtek ALC 298 |
| Wireless | Intel AX201 (wifi+bluetooth) |

**Current OpenCore version: 0.7.2**

## Compatible macOS versions:
 - Big Sur (11.5) (in use)
 - Catalina (10.15) (not tested)

## What Works:
 - Wi-Fi
 - Bluetooth
 - HDMI (video+audio)
 - Audio
 - Webcam and mics
 - All Usb
 - Keyboard
 - Touchpad
 - Sleep/Wake up

## What Doesn't Work:
 - Nvidia GTX1650 Max-Q (Not supported > Disabled)
 - Fingerprint Reader
 - Microsd Card Reader 

## BIOS setting:
 - Secure Boot  > Disabled
 - CFG Lock     > Disabled **

**For disable it: Press L-ALT + R-CTRL + R-SHIFT + F2 or (fn + F2) for see hidden feature. Then go to: Advanced → Power & Performance → CPU - Power Management Control → CPU Lock Configuration → CFG Lock**

## Installation:
 - See Dortania guide > https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
 - Generate yours personal SMBIOS data for MacBookPro15,4
 - with TextEdit put the generated MLB, SerialNo. and UUID in PlatformInfo section of config.plist in OC folder
 - Use my EFI for boot and install macOS

That's all, good hack.
