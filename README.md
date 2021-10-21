# ubuntu-zephyrus-g14

Ubuntu 21.10 installation on ROG Zephyrus G14

## Create the USB Boot Drive

1. Download the Ubuntu 21.10 desktop image:  
   https://releases.ubuntu.com/21.10/ubuntu-21.10-desktop-amd64.iso  
   (This has built-in support for the WiFi chip in the G14.)

2. Write it to the USB drive with a tool like Rufus:  
   https://rufus.ie

## Prepare to Install from USB

1. Turn off drive encryption (BitLocker) in Windows.

2. Turn off fast startup in Windows.

3. Turn off secure boot in the BIOS menu.  
   (Hit ESC before the boot splash screen to enter the menu.)
   
## Boot from USB and Install
   
1. Boot from the USB drive.  
   (Hit ESC before the boot splash screen to enter the menu.)
   
2. Select "Try Ubuntu without installing" first.
   
3. Connect to a WiFi network.  
   (This lets the installer download updates and 3rd-party drivers.)

4. Install Ubuntu.  
   (Recommended: minimal installation alongside Windows, downloading updates, and installing 3rd-party drivers.)

## Verify Functionality

1. Check that the correct Nvidia drivers are installed using the command:  
`nvidia-smi`

## Known Issues

- Bluetooth does not work.
