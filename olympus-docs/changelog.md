# Changelog

## 5/6/2026

### Completed

- Defined Olympus architecture
- Configured Atlas server role
- Configured Tailscale connectivity
- Enabled Wake-on-LAN on Hyperion
- Installed wakeonlan on Atlas
- Successfully woke Hyperion remotely

### Notes

Remote power management is now functional.

## 2026-06-11

### Added

#### UpSnap Deployment

Successfully deployed UpSnap on Atlas using Docker.

##### Purpose

Provide a web-based interface for remote power management within Project Olympus.

##### Features

* Wake-on-LAN management
* Device status monitoring
* Centralised power management dashboard
* Remote access through Tailscale

##### Infrastructure

Host: Atlas

Platform: Docker

##### Managed Devices

* Hyperion

##### Outcome

Project Olympus now includes a dedicated web interface for remotely managing infrastructure power states without requiring direct SSH access or manual script execution.
