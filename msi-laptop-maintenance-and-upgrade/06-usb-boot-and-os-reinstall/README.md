# 06 - USB Boot & Operating System Reinstallation (README)

## Overview
After replacing the battery, the laptop failed to boot and displayed a "No Media Present" error. This indicated that the system could not detect a valid boot device or operating system.

## Issue
- Laptop would not boot into Windows
- Displayed: "Checking Media Presence... No Media Present"
- Bootloader was missing or corrupted

## Diagnosis
- Entered BIOS to verify boot configuration
- Confirmed storage devices were detected
- Identified missing or invalid bootloader

## Solution
1. Created a bootable Windows 10 USB using Microsoft's Media Creation Tool
2. Accessed the boot menu and selected the USB device (UEFI)
3. Booted into Windows installation environment
4. Reinstalled Windows on the primary drive

## Result
- System successfully booted into Windows
- Laptop fully operational
- Verified functionality including Wi-Fi and system stability

## Skills Demonstrated
- BIOS navigation and configuration
- Boot troubleshooting
- USB bootable media creation
- Operating system installation
- Problem diagnosis and resolution
