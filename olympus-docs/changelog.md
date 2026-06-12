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

## 11/6/2026

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

### Homepage

- Deployed Homepage dashboard on Atlas
- Created central service portal
- Added Olympus infrastructure links
- Established foundation for service monitoring and management

##### Outcome

Project Olympus now includes a dedicated web interface for remotely managing infrastructure power states without requiring direct SSH access or manual script execution.

## 12/6/2026

### Added

- Deployed Uptime Kuma on Atlas using Docker
- Added monitoring foundation for Project Olympus
- Planned monitors for Atlas, Hyperion, Homepage, UpSnap, and internet connectivity

### Fixed

- Began troubleshooting Homepage and UpSnap service availability
