# AstroOS Installation Guide

Welcome to the AstroOS installation guide! This document will guide you through the process of installing AstroOS, a customized version of Windows 11. Follow the steps below to ensure a smooth installation.

## Table of Contents

1. [System Requirements](#system-requirements)
2. [Preparing for Installation](#preparing-for-installation)
3. [Creating a Bootable USB Drive](#creating-a-bootable-usb-drive)
4. [Installing AstroOS](#installing-astroos)
5. [Post-Installation Setup](#post-installation-setup)
6. [Troubleshooting](#troubleshooting)

## System Requirements

Before you start, ensure your system meets the following minimum requirements:

- **Processor**: 1 GHz or faster with at least two cores on a compatible 64-bit processor.
- **RAM**: 4 GB or more.
- **Storage**: 64 GB or larger storage device.
- **Graphics**: DirectX 12 compatible graphics / WDDM 2.x.
- **Display**: >9” with HD Resolution (720p).
- **Internet Connection**: Internet connectivity is necessary to perform updates and download and take advantage of some features.

## Preparing for Installation

1. **Backup Your Data**: Ensure all important data is backed up to an external drive or cloud storage.
2. **Download AstroOS ISO**: Obtain the latest version of the AstroOS ISO file from the official website or the source provided.
3. **Product Key**: Ensure you have a valid AstroOS product key.

## Creating a Bootable USB Drive

To install AstroOS, you need to create a bootable USB drive. Follow these steps:

### Using Rufus (Windows)

1. Download and install [Rufus](https://rufus.ie/).
2. Insert a USB drive (8 GB or larger) into your computer.
3. Open Rufus.
4. Under **Device**, select your USB drive.
5. Click **Select** and browse to the location of the downloaded AstroOS ISO file.
6. Ensure the following settings:
   - **Partition scheme**: GPT
   - **Target system**: UEFI (non-CSM)
7. Click **Start** and wait for the process to complete.

### Using Balena Etcher (Windows/Mac/Linux)

1. Download and install [Balena Etcher](https://www.balena.io/etcher/).
2. Insert a USB drive (8 GB or larger) into your computer.
3. Open Balena Etcher.
4. Click **Flash from file** and select the AstroOS ISO file.
5. Select the USB drive.
6. Click **Flash** and wait for the process to complete.

## Installing AstroOS

1. **Insert Bootable USB Drive**: Insert the bootable USB drive into the target computer.
2. **Boot from USB**:
   - Restart your computer.
   - Enter the BIOS/UEFI settings (usually by pressing a key such as F2, F12, Delete, or Esc during startup).
   - Change the boot order to prioritize the USB drive.
3. **Begin Installation**:
   - Save the BIOS/UEFI settings and restart.
   - The computer should boot from the USB drive and display the AstroOS installation screen.
4. **Follow On-Screen Instructions**:
   - Select your language, time, and keyboard preferences, then click **Next**.
   - Click **Install Now**.
   - Enter your product key or choose to enter it later.
   - Accept the license terms and click **Next**.
   - Choose **Custom: Install AstroOS only (advanced)**.
   - Select the partition where you want to install AstroOS. You can delete existing partitions to create new ones if necessary. Click **Next**.
5. **Installation Process**: The installation process will begin. This may take some time. Your computer may restart several times.

## Post-Installation Setup

1. **Initial Setup**:
   - After installation, follow the on-screen prompts to configure your settings, including region, keyboard layout, and network connection.
2. **Sign In with Microsoft Account**: You can sign in with your Microsoft account or create a new one.
3. **Customize Settings**: Customize your privacy settings and other preferences.
4. **Install Updates**: Once you reach the AstroOS desktop, it is recommended to check for and install any available updates via **Settings > Update & Security > Windows Update**.
5. **Install Drivers**: Ensure all necessary drivers are installed. You can use the Device Manager to check for any missing drivers.

## Troubleshooting

### Common Issues

- **Bootable USB Not Recognized**: Ensure the USB drive is properly created and the BIOS/UEFI settings are correctly configured.
- **Installation Freezes**: Try creating the bootable USB drive again using a different tool or USB drive.
- **Missing Drivers**: Download and install the latest drivers from the hardware manufacturer's website.

### Additional Resources

- [AstroOS Official Support](https://astroos.support)
- [Microsoft Windows 11 Troubleshooting](https://support.microsoft.com/en-us/windows)

By following this guide, you should be able to successfully install AstroOS on your computer. Enjoy the enhanced features and performance of AstroOS!
