# Secure-Multi-VLAN-SME-Infrastructure

## Cisco Inter-VLAN Routing with Security (Router-on-a-Stick)

### Overview
This project demonstrates a small enterprise network design using Cisco devices, focused on VLAN segmentation, inter-VLAN routing, and basic network security.
The network simulates three departments (HR, Sales, IT) with controlled communication and secure access.

### Topology
- Technologies & Concepts
- Cisco IOS (Router 2911, Switch 2960)
- VLANs (HR - 10, Sales - 20, IT - 30)
- 802.1Q trunking
- Router-on-a-Stick inter-VLAN routing
- DHCP pools with excluded addresses
- Extended Access Control Lists (ACL)
- Port Security (restrict mode)
- STP PortFast and BPDU Guard
- SSH v2 and local authentication

### Key Features
- Segmented the network into multiple VLANs to isolate departmental traffic.
- Implemented inter-VLAN routing using router subinterfaces.
- Configured centralized DHCP for automatic IP assignment.
- Applied ACLs to restrict sensitive traffic between HR and IT departments.
- Hardened Layer 2 access using Port Security and BPDU Guard.
- Secured device management using SSH instead of Telnet.

### Troubleshooting & Learning
- Identified and corrected a trunk misconfiguration caused by auto-cabling in Packet Tracer.
- Manually reconfigured the uplink to use Gigabit Ethernet for proper inter-VLAN routing.
- Gained hands-on experience with ACL direction and port security violation behavior.

### Files in this Repository
- Secure Multi-VLAN SME Infrastructure.pkt – Packet Tracer simulation file
- configs/ – Router and switch running configurations
- topology.png – Network topology diagram
- screenshots/ – Validation screenshots (ping, DHCP, ACL tests)

### Author
**Selwyn Fernandes**

**CCNA Certified | Aspiring Network Engineer**
