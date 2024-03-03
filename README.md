# kali-linux_setup
Kali Linux Setup Instructions 

Step 1: Download Kali Linux ISO
- Visit the official Kali Linux website at https://www.kali.org/downloads/.
- Choose the appropriate version (32-bit or 64-bit) and download the ISO image.

Step 2: Create Bootable Media
- Use a tool like Rufus (Windows), Etcher (macOS, Linux, Windows), or dd (Linux) to create a bootable USB drive with the Kali Linux ISO.
- Follow the instructions provided by the tool to create the bootable USB drive.

Step 3: Boot from the USB Drive
- Insert the bootable USB drive into your computer and restart it.
- Access the boot menu or BIOS/UEFI settings to set the USB drive as the primary boot device.
- Save the changes and exit the BIOS/UEFI settings to boot from the USB drive.

Step 4: Start the Installation
- Once booted into the Kali Linux live environment, choose the "Graphical Install" option from the boot menu.
- Follow the on-screen instructions to select your language, location, and keyboard layout.

Step 5: Partition the Disk
- Choose the disk where you want to install Kali Linux.
- Select the partitioning scheme (e.g., Guided - use entire disk, Manual) and create partitions as needed.
- Choose the partition to install Kali Linux and continue with the installation.

Step 6: Configure the System
- Set the hostname for your Kali Linux system.
- Create a user account, set a username and password.
- Set the root password when prompted.

Step 7: Select Software
- Choose the software to install. You can select the default options or customize the software selection based on your needs.
- Wait for the installation process to complete.

Step 8: Install GRUB Boot Loader
- Choose the device where you want to install the GRUB boot loader.
- Confirm the installation and proceed.

Step 9: Complete Installation
- Once the installation is complete, you'll be prompted to remove the installation media (USB drive) and restart the system.
- Remove the USB drive and press Enter to reboot the system.

Step 10: Post-Installation Configuration
- After rebooting, log in to your Kali Linux system using the username and password you created during installation.
- Update the system using the package manager. Open a terminal and run the following commands:
bash
Copy code
sudo apt update
sudo apt upgrade
Optionally, configure additional settings such as network configuration, user preferences, and system updates.
