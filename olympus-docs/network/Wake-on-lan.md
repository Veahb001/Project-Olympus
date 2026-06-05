# Wake-on-LAN

## Objective

Allow Atlas to remotely wake Hyperion.

## Components

Atlas:
- Ubuntu Server
- wakeonlan package

Hyperion:
- Ethernet connection
- Wake-on-LAN enabled

## Workflow

Atlas
↓
Wake-on-LAN Packet
↓
Hyperion
↓
Boot Sequence

## Validation

Successfully tested remote wake from Atlas.
