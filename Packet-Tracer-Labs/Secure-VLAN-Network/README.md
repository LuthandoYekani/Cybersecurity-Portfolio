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

![Network Topology](images/01-VLAN-Topology.png)

The topology shows:

- VLAN 10 – Administration
- VLAN 20 – Staff
- VLAN 30 – Guest
- Four interconnected routers
- WAN serial links
- Remote branch networks

---

# VLAN Configuration

Virtual Local Area Networks (VLANs) were implemented to logically separate departments within the enterprise network.

Network segmentation improves security by limiting broadcast domains and controlling communication between user groups.

The following VLANs were created:

| VLAN | Department | Purpose |
|------|------------|---------|
| 10 | Administration | Administrative users |
| 20 | Staff | Internal staff network |
| 30 | Guest | Restricted guest access |

## VLAN Verification

The VLAN database was verified after configuration to ensure each VLAN had been successfully created and assigned to the correct switch ports.

![VLAN Brief](images/02-vlan-brief.png)

The VLAN verification confirmed that:

- VLANs were successfully created
- Ports were assigned correctly
- Department separation was achieved
- Switch configuration matched the network design

---

# Trunk Configuration

Trunk links were configured using IEEE 802.1Q encapsulation to transport traffic for multiple VLANs between switches.

This allows VLAN traffic to traverse the network while maintaining logical separation between departments.

## Trunk Verification

![Trunk Interfaces](images/02-vlan-interfaces-trunk.png)

The trunk configuration confirmed:

- Trunk ports were operational
- VLAN traffic was successfully carried between switches
- Multiple VLANs shared a single physical connection
- Network segmentation remained intact

---

# Security Controls

Network security was strengthened through the implementation of multiple security mechanisms designed to protect network devices, restrict unauthorized access and improve monitoring.

The following security controls were implemented:

- Port Security
- SSH Version 2
- Encrypted Passwords
- Syslog Logging
- Access Control Lists (ACLs)

These controls work together to improve the confidentiality, integrity and availability of the network.

## Port Security

Port Security was configured on access ports to prevent unauthorized devices from connecting to the network.

Security violations were configured to restrict access when an unknown MAC address was detected.

### Port Security Configuration

![Port Security](images/03-port-security.png)

### Port Security Violation Setup

![Port Security Violation](images/04-port-security-violation-setup.png)

### Verification

![Port Security Violation Count](images/05-port-violation-count.png)

The verification confirmed that the configured security policy correctly detected and responded to unauthorized devices.

---

## Secure Remote Administration (SSH)

Secure Shell (SSH) Version 2 was configured to allow encrypted remote administration of network devices.

This provides a secure alternative to Telnet by encrypting management traffic.

### SSH Enabled

![SSH Enabled](images/06-ssh-enabled.png)

### SSH Version 2 Verification

![SSH Version 2](images/07-ssh-v2-enabled.png)

The successful verification confirmed that encrypted remote management was operational.

---

## Password Encryption

Device passwords were encrypted to prevent plaintext credentials from appearing in the running configuration.

### Verification

![Encrypted Passwords](images/08-encrypted-passwords.png)

The configuration confirmed that password encryption was successfully enabled on the network devices.
