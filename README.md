# NOTICE: Project is still in progress
Currently in the process of configuring OS X. As of now, this guide is still incomplete. This repository will be updated as I progress through getting OS X (El Capitan) working on this laptop.

# Mac OS X on the Acer Aspire E5-473-30N5
This repository contains guides and instructions to set up Mac OS X El Capitan on the Acer Aspire E5-473-30N5.

## Laptop Key Specifications
* Intel Core i3-4005U 1.7GHz
* 4GB DDR3L RAM (upgraded to 12GB)
* Intel HD 4400 Graphics
* Qualcomm QCA9377 Network Card (needs to be replaced)
* VGA, HDMI
* 2x USB 3.0, 1x USB 2.0
* Combo 3.5mm headset jack
* ODD
 
## Install Media Creation
Follow [RehabMan](https://github.com/RehabMan)'s [guide](http://www.tonymacx86.com/el-capitan-laptop-support/148093-guide-booting-os-x-installer-laptops-clover.html) on creating an installation media using an App Store-downloaded copy of El Capitan and Clover.

In case the guide is unavailable in the future, here's a mirror and TLDR for the guide. (TODO: Add mirror and TLDR for guide)

### Notes:
* I personally went the UEFI route, but if you prefer Legacy, let me know how well it works out!

## Intel HD 4400 Graphics
Follow [RehabMan](https://github.com/RehabMan)'s [guide](http://www.tonymacx86.com/el-capitan-laptop-support/175797-fix-hd4200-hd4400-hd4600-hd5600-10-11-a.html) on getting Intel HD 4400 working.

In case the guide is unavailable in the future, here's a mirror and TLDR for the guide. (TODO: Add mirror and TLDR for guide)

### Notes:
* VGA works out of the box
* HDMI to be tested (TODO: Test HDMI video + audio)

## Trackpad & Trackpad gestures
Follow [EMlyDinEsHMG](https://github.com/EMlyDinEsHMG)'s [guide](http://forum.osxlatitude.com/index.php?/topic/1948-elan-focaltech-and-synaptics-smart-touchpad-driver-mac-os-x/) on getting the trackpad working.

In case the guide is unavailable in the future, here's a mirror and TLDR for the guide. (TODO: Add mirror and TLDR for guide)

I personally installed *SmartTouchpad v.4.2*, and everything seems to be working fine.

### Scrolling issues:
At first, two-finger scrolling didn't work for me, but doing the following fixes it:

* System Preferences > Trackpad
* Adjust _Scrolling speed_ until scrolling works

### Notes:
* The touchpad as recognized in `geis-tools` on Arch Linux is `ELAN0501:00 04F3:300A`
* 2-5 finger gestures work perfectly

## Sleep/Wake
TODO

## Audio
TODO

## Network
TODO

## Miscellaneous
* ODD works OOB. Haven't tested disc burning, though. (TODO: test disc burning)
