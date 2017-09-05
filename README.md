# Asus-G701VI-Bios
Unlocked versions to enable you to instal Linux into raid enabled laptops.

Linux has still no drivers to support Raid configurations, on Rapid storage controllers.
The only way to install Linux into NVMe devices is not to use the Rapid controller's raid configuration 
but most of gaming laptops, have Raid 0 enabled configurations and no option to break the Raid.

Using this rom, you can disable sata controller, and use your NVMe disks as seperate ones.
Additionally, all manual overclocking features are enabled, including Voltage control.

Follow any guide found in the internet regarding precautions when updating your bios.
Most importantly take a backup of your current bios, preferably using AFUWIN64_v3.05.04.

Upgrade your bios, with the rom provided.
Enter your new bios, find Sata Controller and DISABLE it. That's it.

In order to install some Linux distros, you may need to change boot options, but that's another subject ;-).
