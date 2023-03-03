# Gigabyte-Z77-DS3H-OC-Hackintosh

OpenCore based EFI for Gigabyte Z77-DS3H





## Tested macOS Version

- macOS Mojave 10.14.6
- macOS Catalina 10.15.7


## System Configuration


- Motherboard:  Gigabyte Z77-DS3H
- CPU: Intel Core i7 3770K
- Socket: LGA1155
- RAM: 2x8GB DDR3 @ 1600 Mhz
- iGPU: Intel Graphics HD4000
- dGPU: Sapphire RX 570 4GB
- SSD: Crucial MX500 1TB
- LAN: Atheros GbE LAN
- Audio: ALC887


### BIOS Version

F11a

 
### Bootloader

OpenCore 0.8.9


### SMBIOS

iMac14,4


## BIOS Settings
 

### Enable:

 
- EHCI Hand-off
- Intel xHCI Mode
- Sata Mode: AHCI
- iGPU Memory: 64MB (if using iGPU only)
- Intel Virtualization

 

### Disable:

- Fast Boot
- Secure Boot
- Serial/Com Port
- VT-d
- Parallel Port


## What's working

 - [x] Sleep, Restart, Shutdown
 
 - [x] CPU - Speedstep and power management

 - [x] dGPU
 
 - [x] iGPU
 
 - [x] USB2.0 , USB3.0
 
 - [x] Audio
 
 - [x] Ethernet
 


## What's not working

- So far everything is working great



## Additional Notes


- Don't forget to generate your own SMBIOS with https://github.com/corpnewt/GenSMBIOS. 
 
## ENJOY!
