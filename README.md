# Asus-G701VI-Bios
Unlocked versions to enable you to instal Linux into raid enabled laptops.

I had to install Linux to my laptop, Asus does not support Linux. Period. 

Linux has still no drivers to support Raid configurations, on Rapid storage controllers.
The only way to install Linux into NVMe devices is not to use the Rapid controller's raid configuration 
but most of gaming laptops, have Raid 0 enabled configurations and no option to break the Raid.

Since today, the 5th of September 2017 there is no modded BIOS for the G701VI available anywere else.

Using this rom, you can disable sata controller, and use your NVMe disks as seperate ones.
Additionally, all manual overclocking features are enabled, including Voltage control.

Follow any guide found in the internet regarding precautions when updating your bios.
Most importantly take a backup of your current bios, preferably using AFUWIN64_v3.05.04.

Upgrade your bios, with the rom provided.
Enter your new bios, find Sata Controller and DISABLE it. That's it.

In order to install some Linux distros, you may need to change boot options, but that's another subject ;-).




PS.

1. I am not responsible if you brick your laptop.
2. Usually I do provide support to anyone, but due to workload I will only answer to educated questions.
This is NOT the place to learn about Bios Modding. Instead there are plenty of excellent fora and webpages
where I got my info as well. My favorite is https://www.bios-mods.com/

Extra info:

Original rom G701VIAS.304, has been modded with AMIBCP_v5.0.1 and programed into bios using AFUWIN64_v3.05.04.

Important!!
If you try to mod your own Bios, do NEVER force updating if there are warnings about its size!
In that case, download original rom file, open it with AMIBCP_v5.0.1 and "Save As" another file. 
Mod this new rom file and check again if there are any warning about the size.
Asus WinFlash tool, will not update a modded bios over another of the same version (e.g. if you already have upgraded to G701VIAS.304, WinFlash will notify you that your new Bios is older that the current). But it will still inform you about any size problems, so before updating your bios with AFUWIN64_v3.05.04, try just to open it with WinFlash and check any messages.
If the only message is about older Bios version, proceed updating with the AFUWIN64_v3.05.04.




