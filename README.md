# Proof-of-linux-dual-boot
Proof of dual booting kali linux

### This repository contains a few screenshots of Kali Linux booted up with proof of dual boot and a few linux commands.
## Steps to dual boot Kali Linux

Step 1: On windows open create and format disk and partitions and select (left click) the disk you want to partion, select shrink volume and allocate the space you want to give for Kali (Atleast 60GB is recomended).
Step 2: Download the Kali Linux installer image (.iso file) file from the [Kali Linux website](https://www.kali.org/get-kali/).
Step 3: Download a flashing software such as [rufus](https://rufus.ie/en/) and flash the .iso file into a USB drive. (NOTE: All data in the USB will be erased)
Step 4: Access your computer's BIOS and disable secure boot. (NOTE: If your disk is encrypted with Bitlocker, you also have to decrypt it from windows settings)
Step 5: In the BIOS go to the BOOT menu and boot from the USB.
Step 6: Select the install Kali Linux option and follow every step. (NOTE: WHile choosing the partion select the largest continuous free space option)
Step 7: You have now successfully installed Kali Linux now open the terminal and enter ``` sudo apt install upgrade ``` to get the latest version of every software.
