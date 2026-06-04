# Ubuntu Server Installation

Date: 05-10-2026

## Objective

Create a dedicated server machine for hosting future docker services and infrastructure experiments

## Hardware

Machine: Atlas
Ram: 
Storage: 

## Installation Process

1. Created Ubuntu Server boot USB
2. Installed Ubuntu Server 24.04
3. Configured hostname
4. Created non-root user
5. Enabled SSH access

## Commands Used

```bash
sudo apt update
sudo apt upgrade
sudo apt install openssh-server
```
## Issues Encountered

### Unable to connect via SSH

Cause:
Incorrect IP address.

Solution:

```bash
ip addr
```

## Forgotten Admin Login Details

Cause:
Forgotten Login / Password

Solution:
Access the GRUB menu
Select Recovery
Drop to Root Shell
Remount with Write Permissions
Reset password with "passwd <username>"

Used the correct address and connection succeeded.

## Future Improvements

- Configure firewall
- Install Docker
- Configure Tailscale
```
