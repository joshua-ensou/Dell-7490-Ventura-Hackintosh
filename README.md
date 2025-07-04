# Dell-7490-Ventura-Hackintosh

OpenCore EFI for macOS Ventura on Dell 7490 with Intel i5 8th Gen CPU.


![Dell Github](https://user-images.githubusercontent.com/93620854/212483987-b0142f06-32e7-4b35-bacb-cc1947acd4a5.png)







## Tested macOS Version

- macOS Ventura 13.0 - 13.7


## System Hardware

- CPU:  Intel Core i5-8250U
- iGPU: Intel UHD Graphics 620
- RAM:  8GB 2400Mhz DDR4
- SSD:  SK hynix SC311 SATA 256GB
- WiFi: Intel Wireless 8265
- Display: 1920x1080 FullHD IPS
- Sound Card: Realtek ALC256
- LAN: Intel I219-LM4

### Bootloader

OpenCore 0.8.8


## BIOS Settings

- Boot mode: UEFI
- Fast Boot: Auto
- SecureBoot: Disable
- SATA Mode: AHCI 


### SMBIOS

MacBookPro15,2


## What's working

 
 - [x] CPU Speedstep

 - [x] iGPU acceleration

 - [x] Battery Management
 
 - [x] Sleep/Wake
 
 - [x] Internal Speakers
 
 - [x] Internal Microphone
 
 - [x] WiFi (2.4Ghz + 5Ghz)
 
 - [x] Bluetooth

 - [x] Ethernet

 - [x] HDMI + audio over HDMI

 - [x] Touchpad with Gestures + Trackpad + Buttons

 - [x] Web Camera

 - [x] USB 3.0

 - [x] MicroSD card reader 

 - [x] Native hotkeys support with Fn keys (Volume Fn+F2/F3 and Screen Brightness Fn + F11/F12)
 
 - [x] USB-C Data transfer
 
 - [x] Thunderbolt (needs to plug a device before boot)

 - [x] FileVault 2

 - [x] iMessage
 
 - [x] FaceTime

 - [x] Location Services

 

## Not Tested

 - [x] USB-C charging

 - [x] USB-C DP-alt Mode



## What's not working

 - [x] Connecting to hidden SSD (use itlwm)
 
 - [x] Slow wifi connection to WiFi 6 (11n and 11ac networks are more likely to be selected)



# Notes

OCAuxiliaryTools at https://github.com/ic005k/OCAuxiliaryTools.

OpenIntelWireless at https://github.com/OpenIntelWireless.

SMBIOS at https://github.com/corpnewt/GenSMBIOS. 

Thank you to CloverLeafBG for the initial EFI https://github.com/CloverLeafBG. 🫶🏼
