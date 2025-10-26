# Homelab – Virtualization, Networking & Security

A documented homelab for learning and experiments: Proxmox virtualization, VLAN segmentation on Cisco Catalyst, and UDM Pro gateway/firewall.

## 🧱 Hardware
- Dell PowerEdge R740xd — compute + virtualization
- Cisco Catalyst 9200L-24P-E — L2/L3 switching, PoE
- UDM Pro — gateway, DHCP, firewall
- Storage / SFP+ modules / cabling …

## 🌐 Network Overview
- VLAN “Homelab”: <LAB_VLAN>
- Gateway: <GATEWAY_IP> 
- Services: Proxmox web, iDRAC mgmt
- See detailed notes in [`Docs/network.md`](Docs/network.md)

## 🖼 Diagrams
![Network Topology](Diagram/network_topology.png)
*(exported from draw.io / Excalidraw; source files in `Diagram/`)*

## ⚙️ Configs (sanitized)
- Cisco switch (`Configs/catalyst_9200L.cfg`)
- UDM Pro backup (`Configs/udm_pro.json`)
- Proxmox notes (`Configs/proxmox.md`)
- Docker/K8s (later): `Configs/docker-compose.yml`, `Configs/k8s/`

> **Security:** passwords/keys/IPs that reveal your home should be removed or replaced with placeholders.

## 📊 Monitoring / Logs
Screens + notes in [`Logs/`](Logs/)

## 📌 Roadmap
- [ ] Proxmox templates & backups
- [ ] Docker stack / K8s workers
- [ ] Monitoring: Prometheus/Grafana
- [ ] SIEM/IDS: Wazuh / Suricata
- [ ] GitHub Actions for config lint/backup

## 📝 License
MIT
