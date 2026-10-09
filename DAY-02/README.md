# Linux-Mastery — Day 02

## Command: `sudo resolvectl flush-caches`

**Purpose:** Clear the DNS cache on the system.

### What It Does

This command clears cached DNS records maintained by `systemd-resolved`. It can help troubleshoot DNS resolution issues when accessing websites.

### Command Explained

- `sudo` — Runs the command with administrator privileges.
- `resolvectl` — Manages and inspects the system's DNS resolver.
- `flush-caches` — Clears the DNS cache.

### When to Use

- Troubleshooting DNS resolution issues.
- Clearing cached DNS records before testing website access again.

### Important Note

This command does not change DNS server settings and does not guarantee that every website issue will be fixed.

**Status:** Completed
