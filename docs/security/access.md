# Access & Security

## Current access model (Day 1)
- Remote access is via:
  - Tailscale network
  - SSH key-based authentication

## Accounts
- Server user accounts:
  - (add usernames here)
- Who has access:
  - Me
  - Friend (via tailnet + SSH key)

## SSH security checklist (next)
- [ ] Disable password authentication in `sshd_config`
- [ ] Ensure root login is disabled
- [ ] Consider a separate non-admin user for day-to-day vs admin tasks
- [ ] Confirm only intended public keys exist in `~/.ssh/authorized_keys`

## Tailscale security checklist (next)
- [ ] Review devices in admin console
- [ ] Enable device approval (if not already)
- [ ] Consider ACLs later as you add more services

## Backups (future)
- Decide how we will back up:
  - key configs: sshd_config, tailscale state notes, etc.
  - documentation repo