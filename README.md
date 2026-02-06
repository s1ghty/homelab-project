# homelab-project

Homelab project built on a repurposed laptop to learn Linux administration, networking, and self-hosting.  
Current focus: secure remote access (SSH) and private networking (Tailscale).

## Current status (Day 1)
- ✅ Installed Ubuntu Server on the host laptop
- ✅ Installed + enabled OpenSSH Server
- ✅ Verified local SSH access
- ✅ Installed Tailscale (official install script)
- ✅ Added server + clients to the same tailnet (me + friend)
- ✅ Set up SSH keys for login
- ✅ Configured laptop to keep running with lid closed (so it stays reachable)

## Hardware (current host)
- Huawei Matebook 13
- AMD Ryzen 5 3500U
- 16 GB RAM
- 512 GB SSD
- Wi‑Fi only (no Ethernet port)

## Documentation
- Project log:
  - [2026-02-06 — Day 1: Ubuntu Server + SSH + Tailscale](docs/updates/2026-02-06-day-1.md)
- Network:
  - [SSH](docs/network/ssh.md)
  - [Tailscale](docs/network/tailscale.md)
- Security:
  - [Access & security notes](docs/security/access.md)

## Next steps (planned)
- SSH hardening (disable password auth, confirm root login policy)
- Firewall baseline (UFW) once service ports are known
- Choose first services to self-host (likely Docker + a dashboard + monitoring)
