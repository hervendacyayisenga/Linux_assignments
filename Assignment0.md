# Assignment 0 – Steps to Install Ubuntu

**Name**: Ndacyayisenga Herve
**Student ID**: 24768

## Objective
To outline the necessary steps to install the Ubuntu operating system on a computer.

## Installation Steps

1. **Download the Ubuntu ISO File**
   - Visit the official Ubuntu website (ubuntu.com/download) and download the latest Ubuntu Desktop ISO.

2. **Create a Bootable USB Drive**
   - Insert a USB flash drive (at least 8GB).
   - Use a tool like **Rufus** (built for Windows) or **BalenaEtcher** (available for Mac/Windows/Linux) to flash the downloaded ISO file onto the USB drive.

3. **Boot from the USB Drive**
   - Plug the bootable USB drive into the destination computer.
   - Restart the computer. While it is booting up, repeatedly press the Boot Menu key (often `F12`, `F2`, `F10`, or `DEL` depending on the manufacturer) to open the BIOS/UEFI boot menu.
   - Select the USB drive from the list to boot from it.

4. **Start the Ubuntu Setup**
   - When the GRUB menu appears, select **"Try or Install Ubuntu"**.
   - The Ubuntu live environment will load. Click on the **"Install Ubuntu"** application on the desktop.

5. **Configure Installation Preferences**
   - **Language**: Choose your preferred language.
   - **Keyboard Layout**: Select your keyboard layout.
   - **Network**: Connect to Wi-Fi (recommended for downloading updates during the installation).
   - **Updates and Software**: Choose "Normal installation." Also, check the boxes to download updates while installing and to install third-party software for graphics and Wi-fi hardware.

6. **Partitioning (Installation Type)**
   - Select **"Erase disk and install Ubuntu"** if you want Ubuntu to be the only operating system.
   - *(Alternatively, select "Something else" if you want to set up dual-boot or specify custom partition sizes).*
   - Click **"Install Now"** and confirm the changes to the disk.

7. **Set Timezone and User Info**
   - **Timezone**: Click on your location on the map.
   - **User Information**: Enter your name, choose a computer name, choose a username, and set a strong password.

8. **Finish Installation**
   - Wait for the files to copy and the system to configure. This may take some time.
   - Once completed, a prompt will appear asking you to restart. Click **"Restart Now"**.
   - Remove the USB installation medium when instructed, and press `ENTER`. 
   - The computer will now boot into your freshly installed Ubuntu system.
