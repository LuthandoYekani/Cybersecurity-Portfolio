# Secure VLAN Network

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Cisco Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-blue)
![VLAN](https://img.shields.io/badge/VLAN-Configuration-orange)
![Security](https://img.shields.io/badge/Network-Security-red)

---

# Project Information

**Project Name:** Secure VLAN Network

**Platform:** Cisco Packet Tracer 8.x

**Category:** Network Security

**Status:** ✅ Completed

**Difficulty:** Intermediate

---

# Project Overview

This project demonstrates the implementation of a secure enterprise switched network using Cisco Packet Tracer.

The primary objective was to segment the network using VLANs, implement secure switch configurations, configure SSH for secure remote management, apply Access Control Lists (ACLs), enable Port Security, and monitor network activity using a Syslog server.

The project forms part of my cybersecurity practical training and focuses on secure network administration and defence.

---

# Objectives

- Configure multiple VLANs
- Configure trunk links
- Verify VLAN communication
- Implement Access Control Lists (ACLs)
- Configure Port Security
- Configure SSH Version 2
- Encrypt device passwords
- Configure Syslog logging
- Verify secure network operation

---

# Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- VLANs
- IEEE 802.1Q Trunking
- Access Control Lists (ACL)
- Port Security
- SSH Version 2
- Syslog
- IPv4 Networking

---

# Network Design

The network was designed to demonstrate secure VLAN implementation within an enterprise environment while maintaining connectivity between remote LANs.

The topology consists of:

- Four Cisco 2911 routers
- Five Cisco 2960 switches
- Multiple end-user PCs
- Separate VLANs for different departments
- Redundant WAN links between routers
- Secure remote administration using SSH

The network was segmented to improve security, reduce unnecessary broadcast traffic and enforce communication policies using Access Control Lists.

## Network Topology

![Network Topology](images/01-network-topology.png)

The topology shows:

- VLAN 10 – Administration
- VLAN 20 – Staff
- VLAN 30 – Guest
- Four interconnected routers
- WAN serial links
- Remote branch networks
