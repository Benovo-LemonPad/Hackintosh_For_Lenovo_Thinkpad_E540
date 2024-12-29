# Mac OS Monterey Hackintosh for Lenovo E540.
I decided to make a Hackintosh using OpenCore instead of Clover. A lot of the other ones on Github used outdated versions of Mac OS while, this one uses the latest version of Mac OS supported by this processor.

# What works.
* Trackpad ✔
* Wi-Fi ✔
* Audio ✔
* Camera ✔
* USB ✔

# What doesn't work.
* ALS (Ambiant Light Sensor) ❌
* Bluetooth ❌
* Sleep Mode ❌
* You tell me the rest.

# Preparation.
## You need.
* (Atleast) 4 GB USB.
* Computer running Windows, Mac OS or Linux.

# Installation.
(NOTE) If you have a 32 GB USB or lower, continue with "Formating USBs with smaller storage sizes." If you have a USB with 64 GB or higher scroll down to "Formating USBs with larger storage sizes."

## Formating USBs with smaller storage sizes.
* Windows

1.) Open File Explorer and plug in your USB.

2.) Right click on your USB drive and click format.
 
![Screenshot 2024-12-28 214509](https://github.com/user-attachments/assets/17261f1f-1901-4035-8dd2-0efa5e849572)

3.) Make sure your USB filesystem is FAT32, the name is EFI (case sensitive) and click on Start. (NOTE) This will erase all data from the USB!

![Screenshot 2024-12-29 000755](https://github.com/user-attachments/assets/913ba9f3-ef19-49e9-9f11-be5f86d5c042)

* Mac OS/Linux

  Sorry, there is no tutorial for Mac OS and Linux.

## Formating USBs with larger storage sizes.
* Windows

We will be using a free piece of software called Rufus which you can download at <a href="https://rufus.ie" target="_blank">https://rufus.ie.</a>

1.) Run the program and plug in your USB.

2.) Make sure that Rufus is set like this.

### Device Properties

* Device is your USB.
* Boot selection is non bootable.
* Partition scheme is GPT.

### Format Options

* Volume label is EFI (case sensitive).
* File system is Large FAT32.

![Screenshot 2024-12-29 005908](https://github.com/user-attachments/assets/d5ea7fd6-239d-47f7-9be2-430e279990d9)

3.) Click on START and then OK. (NOTE) This will erase all data on the USB!

* Mac OS/Linux

  Sorry, there is no tutorial for Mac OS and Linux.

## Getting the Mac OS installer.

1.) Download the 
