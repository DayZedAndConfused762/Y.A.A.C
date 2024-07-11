<!-- ======================================== yaac1-setup.md Start ======================================== -->


<!-- ------------------------------ Intro Start ------------------------------ -->

# Y.A.A.C-1 - Setup

Steps to setup and install operating systems and software on the Y.A.A.C-1.

<!-- ------------------------------ Intro End ------------------------------ -->


<!-- ------------------------------ Overview Start ------------------------------ -->

<!-- ------------------------------ Overview End ------------------------------ -->


<!-- ------------------------------ Bootloader Start ------------------------------ -->

## Bootloader

**Change Raspberry Pi Boot to USB**
* Image a SD card with 'Bootloader (Pi 4 family)' using [Raspberry Pi Imager](https://www.raspberrypi.com/software/).
* Boot the Raspberry Pi with SD card, choose USB as the first boot option (Will boot from USB if present, then fallback to SD Card if no USB device)

<!-- ------------------------------ Bootloader End ------------------------------ -->


<!-- ------------------------------ OS 1 Start ------------------------------ -->

## Operating System 1

**Internet in a Box - Rasperry Pi OS Bookworm - Crucial 1TB SSD**
* Image 'Raspberry Pi OS Full (64-bit)' using [Raspberry Pi Imager](https://www.raspberrypi.com/software/).
* Expand File System - Run: `sudo raspi-config`. Choose [1] Expand File System. Follow the onscreen instructions. Reboot the Raspberry Pi
* Update software - `sudo apt update` and `sudo apt full-upgrade`
* Setup SSH
* Install Internet in a Box - from command line enter `curl iiab.io/install.txt | bash`

<!-- ------------------------------ OS 1 End ------------------------------ -->


<!-- ------------------------------ OS 2 Start ------------------------------ -->

## Operating System 2

**CyberSecurity - Kali Linux - 512 GB Sandisk Micro SD Card**
* https://www.kali.org/docs/

<!-- ------------------------------ OS 2 End ------------------------------ -->


<!-- ------------------------------ OS 3 Start ------------------------------ -->

## Operating System 3
**General Use - Raspberry Pi OS Bookworm - SanDisk 1TB Extreme Portable SSD**

* Image 'Raspberry Pi OS Full (64-bit)' using [Raspberry Pi Imager](https://www.raspberrypi.com/software/).
* Expand File System - Run: `sudo raspi-config`. Choose [1] Expand File System. Follow the onscreen instructions. Reboot the Raspberry Pi
* Update software - `sudo apt update` `sudo apt full-upgrade`
* Setup SSH

<!-- ------------------------------ OS 3 End ------------------------------ -->


<!-- ------------------------------ Outro Start ------------------------------ -->

<!-- ------------------------------ Outro End ------------------------------ -->


<!-- ======================================== yaac1-setup.md End ======================================== -->
