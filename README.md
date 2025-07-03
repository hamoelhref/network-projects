
# 🏢 Simple Office Network Project (Cisco Packet Tracer)

This project simulates a secure and scalable enterprise office network using Cisco Packet Tracer. It features full VLAN segmentation, centralized DHCP, VTP for VLAN propagation, and inter-VLAN routing using a router-on-a-stick model.

## 🔧 Features
- **VLANs** for department isolation: Sales (10), HR (20), IT (30)
- **Router-on-a-Stick** for inter-VLAN routing
- **VTP** for VLAN database synchronization across switches
- **DHCP** configuration on the router with IP pools and exclusions
- **Trunking** between switches and router

## 🔐 Security Features
- **DHCP Snooping** to prevent rogue DHCP servers
- **Dynamic ARP Inspection (DAI)** for ARP spoofing protection
- **BPDU Guard** to prevent unauthorized switch connections
- **PortFast** enabled on access ports for faster convergence

## 🛠 Tools & Technologies
- Cisco Packet Tracer
- VLANs, VTP, DHCP, Trunking
- DAI, DHCP Snooping, BPDU Guard
- Router-on-a-Stick
- Subinterface Configuration
- Switch Security Best Practices

## 📁 Network Topology
- 3 Switches (1 Core, 2 Access)
- 1 Router
- 6 PCs (spread across VLANs)
- 1 External DHCP Server (optional scenario)

## 👨‍💻 Author
**Mohamed Ibrahim** – aspiring network engineer with a focus on secure LAN design.
