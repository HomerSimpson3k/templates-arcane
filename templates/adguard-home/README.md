# AdGuard Home

AdGuard Home needs to bind DNS ports on the host. If another DNS service such as Pi-hole or systemd-resolved is already using port 53, change `DNS_PORT` or stop the conflicting service before starting this stack.

The setup wizard is exposed on `SETUP_PORT`. After the first run, the normal web UI is available through `WEB_PORT`.
