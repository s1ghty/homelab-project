# SSH Access

## Purpose
Secure remote access to the homelab server.

## Method
- SSH over Tailscale network
- Key-based authentication

## Setup Steps
1. Install OpenSSH server
2. Enable SSH service
3. Generate ed25519 SSH key on client
4. Add public key to server

## Notes
- authorized_keys file controls access
- Each line = one allowed device

## Future Improvements
- Disable password authentication
- Separate users

