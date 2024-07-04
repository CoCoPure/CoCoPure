**CoCoPure** is a fast and convenient operating system with many packages to help you create your own system. For more information, including our documentation, please visit https://CoCoPure.github.io

>[!WARNING]
>Devices with Arm processor architecture such as Raspberry Pi are not supported

# Getting Started

## Installation

>[!NOTE]
>If you use Android, you can use "Pi sd card imager" to burn .iso

So you want to install CoCo Pure. First, download the [Coco .iso file](https://github.com/CoCoPure/CoCoPure/releases). Then use any flasher to burn the .iso file to a USB drive. Some of the most popular are rufus, balena etcher and raspberry pi imager

## First Boot

>[!NOTE]
>If you know how to install the system from a bootable USB, you can skip this step

If you have successfully completed the previous step, you can now insert the USB drive into your computer. Now enter the computer's BIOS, most often when turning on the computer you need to click one of the following buttons: esc, left shift, enter, f2, f12, f9 when we are in bios, we need to disable the **"secure boot"** option and change the boot order so that the system starts from our USB drive and not from the Windows boot manager (for Windows), now save the changes and turn on the computer. Congratulations, you have successfully launched CoCoPure from your USB drive.

## Post Installation

so we are in our system, but what now, we don't have graphics, only a black console, and to have graphics we have to install them from ready-made packages. for more info read the [**Gui Setup**](https://github.com/CoCoPure/CoCoPure/wiki/GUI#gui-setup) sections in the official documentation.
