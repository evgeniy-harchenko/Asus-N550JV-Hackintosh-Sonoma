# Asus-N550JV-Hackintosh
 Asus-N550JV-Hackintosh EFI Opencore

This repository is about hackintosh on **Asus-N550JV**. For now, all the hardware is working as expected, it's ready for daily usage and I will continue to follow the updates of OpenCore and macOS.

Anyone who has the same board can use my EFI directly. The source EFI folder uses debug version of OpenCore, mainly used for installation and testing. It’s recommended to use the release version for daily usage, you can replace it yourself or just download my release. Either way, don’t forget to edit the `EFI/OC/config.plist` file, you should generate your own SMBIOS info by following the [Haswell Config Guide #PlatformInfo](https://dortania.github.io/OpenCore-Install-Guide/config.plist/haswell.html#platforminfo). 

Highly recommended reading the whole [OpenCore Install Guide](https://dortania.github.io/OpenCore-Install-Guide/) before you start.

## Hardware

* Motherboard: Asus N550JV
    * Ethernet: Realtek RTL8168/8111
    * Wi-Fi/BT: Intel(R) Dual Band Wireless N 7260
* CPU: Intel Core i7-4700HQ
* iGPU: Intel HD Graphics 4600
* eGPU: GeForce GTX 750M (disable)
* RAM: DDR3L 1600 8GB

## BIOS Setting after installation
For fixing CFG lock follow
[this section](https://dortania.github.io/OpenCore-Post-Install/misc/msr-lock.html)
from [dortania](https://github.com/dortania)'s guide.

## Software

* Bootloader: OpenCore 1.0.4
* OS: macOS Sonoma 14.5 (MacBookPro 15,3)


## Thanks

- Sonoma Install Guide [GeekyCoder7/OpenCore-EFI-Lenovo-Y50-70](https://github.com/GeekyCoder7/OpenCore-EFI-Lenovo-Y50-70/) 
- asusn550jv-hackintosh [superrnovae/asusn550jv-hackintosh](https://github.com/superrnovae/asusn550jv-hackintosh/) 
- hackintosh-n550 [rubinda/hackintosh-n550](https://github.com/rubinda/hackintosh-n550/) 
- SimpleMSR [arter97/SimpleMSR](https://github.com/arter97/SimpleMSR/) 
 
