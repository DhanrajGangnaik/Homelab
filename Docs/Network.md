# Network Design

## Addressing
- VLAN 50: `<PRIVATE_SUBNET>/24` (example: 192.168.X.X/24)
- Gateway: `<GATEWAY_IP>`
- DHCP scope: `<DHCP_RANGE>` (e.g., 192.168.X.100–200)

## Switching & Trunks
- Uplink: UDM Pro SFP+ <-> Catalyst SFP+
- Trunk VLANs: 50
- Access ports: list (port -> device)

## Firewall / Rules (high level)
- Allow LAN <-> Proxmox UI
- Block IoT -> Homelab (future)

## Notes
- mgmt IPs (obfuscated with `<MGMT_IP>`)
- backup/restore commands
