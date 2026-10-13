# Media Server Home Lab

Repurposed a desktop PC into a self-hosted media server using Ubuntu Server Linux and Jellyfin to manage and stream movies and television shows across devices on a local network.

## PC Specs
- Intel Core i5-6500 processor
- 16 GB RAM
- 2 TB Toshiba HDD
- NVIDIA GeForce GTX 1650 Super

## Objective
Create centralized digital storage of my favorite physical media and be able to access it whenever, wherever, without the reliance on monthly subscriptions or network instability.


## Potential Issues
> [!WARNING]
> - HDD is corrupted/damaged.
>    - On startup, it used to click (resolved)
 >   - Constant '100% Usage'
> - PSU was replaced after it died.


## Setup
The PC is currently running on Windows 10. With the age and issues of this device, boot times are horrendous (5-15 mins). Thankfully, I have 0 need for this bloated OS. 

1. Download the [Ubuntu Server ISO image](https://ubuntu.com/download/)
2. Create a bootable USB flash drive
3. Plug into PC and boot

> [!Note]
> I chose to run Ubuntu Server without a GUI, so I had to rely on SSH and the terminal to install software, configure services, manage files, and troubleshoot any issues.
