# Homelab project

Personal homelab built on a repurposed laptop (Huawei Matebook 13) for learning Linux, networking, and self-hosting.

## Current stage (Day 1)
✅ Ubuntu Server installed  
✅ OpenSSH installed + key-based SSH access working  
✅ Tailscale installed + remote access working (me + friend)  
✅ Laptop configured to keep running with lid closed  

## Hardware
- Host: Huawei Matebook 13
- CPU: AMD Ryzen 5 3500U
- RAM: 16 GB
- Storage: 512 GB SSD
- Network: Wi‑Fi only (no Ethernet port)

## Access
- **Primary remote access:** SSH over Tailscale
- Docs:
  - [SSH](docs/network/ssh.md)
  - [Tailscale](docs/network/tailscale.md)
  - [Access/Security notes](docs/security/access.md)

## Project log
- [2026-02-06 — Day 1: Base server, SSH, Tailscale](docs/updates/2026-02-06-day-1.md)

## Next goals
- Document current configuration (this repo)
- Basic hardening (disable password SSH, firewall review)
- Pick and deploy first services (likely Docker + a dashboard + monitoring)