# Tailscale

## Purpose
Provide secure remote access to the homelab server (and services later) from anywhere without port forwarding.

## Approach
- Tailscale installed on the Ubuntu Server host
- Tailscale installed on client devices (phone, laptops)
- Access is primarily:
  - SSH over Tailscale IP
  - (later) web services via `http://<tailscale-ip>:port`

## Day 1 setup (high level)
1. Install Tailscale on Ubuntu Server
2. Authenticate the server into the tailnet
3. Confirm `tailscale status` shows devices
4. Invite friend into the same tailnet
5. Confirm friend’s device appears under admin console and can connect

## Useful commands
- Status:
  - `tailscale status`
- Get Tailscale IP:
  - `tailscale ip -4`
- Bring interface up (interactive auth may be required):
  - `sudo tailscale up`

## Notes
- Works well behind Verizon 5G Home Internet router (no inbound ports required)
- Treat tailnet membership as privileged access (only invite trusted devices/users)