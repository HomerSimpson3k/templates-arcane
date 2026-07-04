# Home Assistant

This is the Home Assistant Container deployment, not Home Assistant OS or Supervised. Add-ons, backups, and OS-level management from HAOS are not included.

The template uses host networking to preserve local discovery behavior for integrations that rely on mDNS, SSDP, Bluetooth, or other LAN broadcasts. The UI is available on port 8123 of the host.
