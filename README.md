# Homelab

Self-hosted lab built on Proxmox for hands-on experience with virtualization,
Docker, networking, and remote access. Started July 2026.

## Overview
- Proxmox host running Ubuntu Server VMs
- Docker Compose services on a dedicated 192.168.100.x subnet
- Remote access over Tailscale; HTTPS with locally trusted certificates (mkcert)
- OpenWrt on a TP-Link TL-WDR4300 providing a WISP-mode uplink
- Seafile for self-hosted file-sharing

## Services
| Service | Stack | Notes |
|---|---|---|
| Seafile | Docker Compose, MariaDB, Memcached | Self-hosted file sharing |
