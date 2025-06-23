# Hackintosh-MSI-GP63-Leopard-8RE-Sequoia-15.4.1
OpenCore Based EFI For msi-gp63-leopard-8re i7 8750H Kaby Lake
Tested on Sequoia-15.4.1


to fix wifi, you can follow this step :
https://elitemacx86.com/threads/how-to-fix-intel-wifi-and-bluetooth-on-macos-sequoia-and-later.2066/#-step-4-add-bluetooth-parameters


## Warning !
Don't forget to enter your serial number before putting the config.plist file into the EFI folder.
Use THIS In SMBIOS Tools =>    MacBookPro15,1



## Specs

| Name             | Details                                                                |
| ----------------- | ------------------------------------------------------------------ |
|Model|GP63-Leopard-8RE|
| CPU | Intel Core i7-8750H 6 x 2.2 - 4.1 GHz   |
| CPU Family |  Coffee Lake-H  |
| WiFi Chipset |Intel Wireless-AC 9560 160MHz  |
| Audio Codec |  ALC 235  |
| NVME |  TEAM_TM8FP6256GVC3S500J |


##  Whats Working 

Bluetooth ✅

Sound    ✅

Keyboard ✅

TrackPad ✅

Function Key ✅

## Bugs
- AirDrop
- Wifi

## BIOS Setting 
### Disable 
- Fast Boot
- Secure Boot
  
### Enable
- Boot Mode UEFI
- SATA Mode: AHCI
- Hyper-Threading

For more about BIOS Follow This Guide For Detailed Info

https://dortania.github.io/OpenCore-Install-Guide/config-laptop.plist/coffee-lake-plus.html#intel-bios-settings


## Thanks 




- [@HolyHobo-chan](https://github.com/HolyHobo-chan/MSI-Leopard-GP63-Hackintosh) for USBmap
- [@devendramilmile121](https://github.com/devendramilmile121/msigl638rc-hackintosh-efi) for EFI config
- [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/)

