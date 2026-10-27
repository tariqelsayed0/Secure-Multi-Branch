# Secure Multi-Branch Enterprise Network

A Cisco Packet Tracer project that simulates a secure enterprise network connecting multiple company branches through a structured LAN/WAN infrastructure.

## 📌 Project Overview

This project focuses on designing and implementing a multi-branch enterprise network connecting **Alexandria, Cairo, and Tanta**.

The network provides inter-branch communication, department segmentation, centralized IP address assignment, Internet connectivity, and secure site-to-site VPN tunnels.

The main goal is to combine enterprise routing, switching, and network security technologies in one integrated simulation.

## 🏗️ Network Architecture

The simulated infrastructure includes three branches:

- **Alexandria:** VLAN segmentation, Layer 3 switching, inter-VLAN routing, and VPN connectivity.
    
- **Cairo:** Routing, multiple internal subnets, DHCP services, and VPN connectivity.
    
- **Tanta:** NAT/PAT, Internet connectivity, wireless access, and VPN connectivity.
    

The branches communicate through a **Full-Mesh GRE over IPsec VPN** design, allowing each branch to establish a secure connection with the other two branches.

## 🛠️ Technologies Implemented

- **VLANs:** Logical segmentation of departments.
    
- **Layer 3 Switching:** Inter-VLAN routing.
    
- **Static Routing:** Communication between routers and network subnets.
    
- **DHCP:** Automatic IP address assignment.
    
- **NAT/PAT:** Internet connectivity for internal devices.
    
- **GRE Tunneling:** Logical tunnels between branch routers.
    
- **IPsec VPN:** Encryption and protection of inter-branch traffic.
    
- **Full-Mesh VPN:** Direct secure connectivity between all three branches.
    
- **Access Control Lists (ACLs):** Traffic filtering and access control.
    
- **Port Security:** Switch-port access protection.
    
- **DHCP Snooping:** Protection against unauthorized DHCP servers.
    
- **EtherChannel:** Link aggregation and improved link availability.
    
- **Wireless Networking:** Wireless connectivity, including guest access.
    

## 🔐 VPN Architecture

The project combines GRE tunneling with IPsec encryption to provide secure communication across the simulated WAN.

The full-mesh design includes these branch-to-branch connections:

- Alexandria ↔ Cairo
    
- Alexandria ↔ Tanta
    
- Cairo ↔ Tanta
    

GRE provides the logical tunnels, while IPsec protects traffic transmitted through the VPN infrastructure.

## 🧪 Testing and Verification

The project report covers verification scenarios for:

- Connectivity between branches.
    
- Inter-VLAN communication.
    
- DHCP address assignment.
    
- NAT/PAT and Internet connectivity.
    
- GRE tunnel status.
    
- IPsec security associations and encrypted communication.
    
- ACL traffic filtering.
    
- Overall network operation and troubleshooting.
    

## 🚀 How to Open the Project

1. Download or clone this repository.
    
2. Install Cisco Packet Tracer.
    
3. Open the `.pkt` file in Cisco Packet Tracer.
    
4. Inspect the topology and device configurations.
    
5. Use simulation mode and appropriate verification commands to investigate network behavior.
    

## 📂 Repository Contents

- `MultiBranch.pkt` — Cisco Packet Tracer network simulation.
    
- `README.md` — Project overview, technologies, and usage instructions.
    
- `docs/` — Project report and supporting documentation, if included.
    
- `screenshots/` — Network topology and selected verification results, if included.
    

## 🎯 Learning Outcomes

This project demonstrates practical work with enterprise network design, routing and switching, network segmentation, WAN connectivity, VPN configuration, and network troubleshooting.

It brings together multiple networking concepts in a single simulated enterprise environment.

## ⚠️ Disclaimer

This project is an educational simulation developed using Cisco Packet Tracer. Its behavior and supported features depend on the devices and capabilities available in the simulator.

---

**Tools:** Cisco Packet Tracer  
**Project Type:** Enterprise Networking / Network Security  
**Branches:** Alexandria, Cairo, Tanta