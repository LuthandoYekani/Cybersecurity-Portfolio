# Enterprise Full Mesh Network Design Report

---

## Executive Summary

This project involved designing and implementing a secure enterprise network in Cisco Packet Tracer using a four-router full mesh topology.

The objective was to build a resilient network infrastructure that provides reliable communication between multiple Local Area Networks (LANs) through redundant Wide Area Network (WAN) links. The project also focused on applying secure network configuration practices, verifying connectivity and demonstrating practical networking skills relevant to enterprise environments.

The implementation was completed as part of the Occupational Certificate: Cybersecurity Analyst (NQF Level 5) practical programme.

---

# Project Objectives

The primary objectives were to:

- Design an enterprise network topology
- Configure Cisco routers and switches
- Implement IPv4 addressing
- Configure WAN serial links
- Implement static routing
- Verify connectivity across all LANs
- Demonstrate troubleshooting techniques

---

# Network Architecture

The enterprise network consists of:

| Device | Quantity |
|---------|----------|
| Cisco 2911 Routers | 4 |
| Cisco 2960 Switches | 4 |
| PCs | 8 |
| LAN Networks | 4 |
| WAN Serial Links | 6 |

A full mesh topology was selected to provide redundant communication paths between all routers.

---

# IP Addressing Scheme

| Network | Address |
|---------|-----------|
| LAN 1 | 192.168.10.0/28 |
| LAN 2 | 192.168.20.0/28 |
| LAN 3 | 192.168.30.0/28 |
| LAN 4 | 192.168.40.0/28 |
| WAN Links | /30 |

---

# Configuration Highlights

The following configurations were completed:

- Router interface configuration
- Switch configuration
- IPv4 addressing
- Static route configuration
- WAN serial interface configuration
- LAN connectivity
- End-to-end routing verification

---

# Testing and Validation

The network was tested using:

- Successful ICMP ping tests
- Interface verification
- Routing table verification
- End-to-end connectivity testing

The successful ping tests confirmed that routing and addressing were configured correctly across all four LANs.

---

# Challenges

During implementation several challenges were encountered including:

- Static route troubleshooting
- WAN addressing verification
- Interface configuration
- Connectivity testing

Each issue was resolved through systematic troubleshooting using Cisco IOS diagnostic commands.

---

# Lessons Learned

This project improved my practical understanding of:

- Enterprise network design
- Static routing
- IPv4 subnetting
- WAN technologies
- Cisco IOS configuration
- Network troubleshooting methodologies

---

# Future Improvements

Future versions of this network could include:

- Dynamic routing (OSPF)
- VLAN segmentation
- Access Control Lists
- DHCP services
- Network monitoring
- SSH device hardening
- Syslog logging

---

# Skills Demonstrated

- Enterprise Networking
- Cisco IOS
- IPv4
- Static Routing
- Network Design
- WAN Technologies
- Troubleshooting
- Documentation

---

# Conclusion

This project demonstrates the practical implementation of an enterprise network using Cisco Packet Tracer. The completed topology provides secure and reliable communication between multiple LANs while showcasing core networking principles including routing, addressing and network verification.
