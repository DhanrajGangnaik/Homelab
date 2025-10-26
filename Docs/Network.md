# Network Design
## Addressing
- VLAN 50: 192.168.50.0/24
- Gateway: 192.168.50.1
- DHCP scope: 192.168.50.100–200 (example)

## Switching & Trunks
- Uplink: UDM Pro SFP+ <-> Catalyst SFP+
- Trunk VLANs: 50
- Access ports: list (port -> device)

## Firewall / Rules (high level)
- Allow LAN <-> Proxmox UI
- Block IoT -> Homelab (future)

## Notes
- mgmt IPs (obfuscated)
- backup/restore commands
