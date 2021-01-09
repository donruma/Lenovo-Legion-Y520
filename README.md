# Lenovo-Legion-Y520

This repository is a buckup data for my OpenCore EFI hackintosh 

##  Specification

Intel Core i7-7700HQ Processor 2.81GHz

16.0GB DDR4 SODIMM 2400MHz

NVIDIA GeForce GTX1050Ti (Disabled)

Intel HD 630 1536MB

Intel(R) Dual Band Wireless-AC 3165

Realtek Lan

### OS  :
Catalina 10.15.7

Big Sur 11.1


## What works
 
Accelerated graphics for HD630 including OpenCL & Metal.  

Native USB3/USB2/USB-C.  

Native audio with AppleHDA, including headphones.  

Built-in camera.  

Native power management.  

Battery status.  

Built-in keyboard.  

Built-in trackpad.  

Backlight controls.  

Wired Ethernet Lan.  

Build-in WiFi.

Messages/FaceTime.  

HDMI

Bluetooth

## What does not work

SDcard "if someone has Kext or SSDTs let me know"

## BIOS configuration :
- Set BIOS to defaults.
- UEFI boot is enabled.
- Secure boot is disabled.
- Fast boot is disabled.
- SATA mode is set to AHCI.
- Intel Virtualization Technology is enabled.

## Post Installation
use OpenCore Configurator to mount the efi
- replace EFI folder in EFI Volumes from your USB EFI

## Note

#### I change my "Platforminfo" and I put new info so u only need to add ur MAC Address to the ROM value after install follow the [Fixing iServices](https://dortania.github.io/OpenCore-Post-Install/universal/iservices.html#generate-a-new-serial") page on how to find your real MAC Address
