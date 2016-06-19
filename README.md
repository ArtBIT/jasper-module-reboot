Jasper-Module-Reboot
======================

Jasper Reboot Module for my [HAL9000 Raspberry PI Instructable](http://www.instructables.com/id/RaspberryPI-HAL9000/)
Reboot your RaspberryPI using your voice.

##Steps to install Reboot Module

* run the following commands in order:
```
git clone https://github.com/ArtBIT/jasper-module-reboot.git
cp jasper-module-reboot/Reboot.py <path to jasper/client/modules>
#i.e. cp jasper-module-reboot/Reboot.py /usr/local/lib/jasper/client/modules/
```
* Restart the Pi:
```
sudo reboot
```
##Congrats, JASPER Reboot Module is now installed and ready for use
Here are some examples:
```
YOU: Reboot
JASPER: *sings daisy daisy and reboots*
YOU: Restart
JASPER: *says a witty remark and reboots*
```

