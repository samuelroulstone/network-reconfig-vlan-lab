# 🔧 Network Reconfiguration & VLAN Lab

> Reconfiguration of an existing enterprise network's addressing and VLAN structure, built as part of SNHU CYB-210 (Network Security).

## 📋 Overview

Took over an existing (pre-built) network topology in Cisco Packet Tracer and reconfigured its IP addressing scheme, default gateways, and DHCP/DNS services across admin workstations and printers. Documented the updated VLAN table, wireless settings, device layout, and camera configuration in an accompanying network modification brief.

## 🎯 Objective

Update an existing network to reflect new addressing requirements while maintaining connectivity and correct VLAN segmentation for all endpoint types (workstations, printers, wireless clients).

## 🧰 Tools & Concepts

- Cisco Packet Tracer
- IP address & gateway reconfiguration
- VLAN table documentation
- DHCP & DNS service updates
- Wireless network configuration
- NAT

## 🔍 Methodology

1. **Readdressing** — changed the default gateway to 192.168.12.1 for PC1Admin, PC2Admin, PC3Admin, and the Admin Printer, and assigned new static IPs (192.168.12.101–.103 for the PCs, .150 for the printer).
2. **Routing table cleanup** — removed the old subnet configurations and added the two new ones (192.168.12.0 and 192.168.20.0).
3. **NAT configuration** — used CLI commands on the subnet router to define NAT inside and outside interfaces.
4. **DHCP updates** — edited the DHCP configuration on Server Main with the correct IP address and range, then repopulated it for all admin devices.
5. **DNS updates** — updated the DNS configuration on Server Main to reflect the new IP addressing.
6. **Documentation** — captured the updated VLAN table, wireless settings, device layout, camera configuration, network diagram, and ping test results in a separate network modification brief.

## ✅ Key Outcomes

- Successfully reconfigured addressing and gateways for all admin workstations and the admin printer
- Cleaned up and replaced outdated subnet configurations with the new 192.168.12.0 and 192.168.20.0 networks
- Verified NAT inside/outside configuration via CLI
- Documented the full VLAN table, wireless settings, and network diagram with supporting screenshots and passing ping results

## 🧠 Skills Demonstrated

`Cisco Packet Tracer` `VLANs` `DHCP` `DNS` `NAT` `Network Documentation` `Wireless Configuration`

## 📁 Files

- [`docs/5-2_Activity__Packet_Tracer.docx`](docs/5-2_Activity__Packet_Tracer.docx) — write-up and screenshots of the readdressing, NAT, DHCP, and DNS reconfiguration
- [`docs/CYB_210_Module_Five_Activity_Packet_Tracer_Samuel_Roulstone.pkt`](docs/CYB_210_Module_Five_Activity_Packet_Tracer_Samuel_Roulstone.pkt) — Packet Tracer lab file
- [`docs/Network_Modification_Brief_Screenshots.docx`](docs/Network_Modification_Brief_Screenshots.docx) — VLAN table, wireless settings, device/camera layout, network diagram, and ping test screenshots

---
🔗 Part of my [cybersecurity portfolio](https://samuelroulstone.com) · [Back to profile](https://github.com/samuelroulstone)
