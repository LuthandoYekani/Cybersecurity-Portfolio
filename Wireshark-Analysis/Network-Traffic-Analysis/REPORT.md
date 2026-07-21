# Network Traffic Analysis using Wireshark

## Executive Summary

This project demonstrates the practical use of Wireshark to capture, filter, and analyse network traffic within a controlled CyberLab environment. Network packets exchanged between a Kali Linux monitoring system and an Ubuntu virtual machine were captured and analysed to understand communication patterns and identify protocol behaviour.

Display filters were used to isolate ARP and ICMP traffic, allowing detailed inspection of packet exchanges and demonstrating techniques commonly used by cybersecurity analysts during network troubleshooting and security investigations.

---

## Objectives

The objectives of this project were to:

- Capture live network traffic using Wireshark.
- Analyse packet exchanges between network hosts.
- Apply display filters to isolate specific protocols.
- Interpret ARP and ICMP traffic.
- Understand the security significance of captured packets.
- Develop practical network analysis skills.

---

## Scope

The analysis was performed within an isolated CyberLab environment using virtual machines connected to an internal virtual network. The project focused exclusively on analysing ARP and ICMP traffic generated during normal network communication and connectivity testing using Wireshark.

No malicious traffic was intentionally introduced during this investigation.

---

## Lab Environment

| Component | Description |
|-----------|-------------|
| Monitoring System | Kali Linux |
| Target System | Ubuntu Linux |
| Packet Analysis Tool | Wireshark |
| Virtualisation Platform | Oracle VirtualBox |
| Network Type | Internal Virtual Network |

---

# Methodology

The investigation followed a structured packet analysis process:

1. Configure the CyberLab virtual environment.
2. Start Wireshark packet capture on the monitoring system.
3. Generate network traffic between the Kali Linux and Ubuntu virtual machines.
4. Apply display filters to isolate specific network protocols.
5. Inspect packet details and communication behaviour.
6. Analyse the captured traffic and document security observations.

---

# Packet Analysis

## Address Resolution Protocol (ARP)

The ARP display filter was applied to isolate Address Resolution Protocol packets. The captured traffic showed hosts resolving MAC addresses before communication occurred on the local network.

The packet exchange demonstrated the normal operation of ARP and illustrated how devices discover hardware addresses before transmitting data across the local network.

---

## Internet Control Message Protocol (ICMP)

The ICMP display filter isolated Echo Requests and Echo Replies generated during connectivity testing.

The captured packets confirmed successful communication between the Kali Linux monitoring workstation and the Ubuntu virtual machine. Packet analysis verified successful request and response exchanges with no packet loss during testing.

---

# Findings

The investigation identified the following:

- Successful ARP communication between hosts.
- Successful ICMP Echo Requests and Echo Replies.
- Proper packet exchange within the isolated CyberLab environment.
- Effective use of Wireshark display filters to isolate protocol-specific traffic.
- No malicious or abnormal traffic observed during the controlled laboratory exercise.

---

# Security Recommendations

Based on the analysis, the following recommendations are made:

- Continuously monitor network traffic for abnormal ARP behaviour that may indicate ARP spoofing attacks.
- Monitor ICMP traffic for excessive host discovery or reconnaissance activity.
- Apply protocol-specific filters during investigations to improve analysis efficiency.
- Maintain packet captures during incident investigations to preserve forensic evidence.
- Perform regular packet analysis as part of network security monitoring activities.

---

# Conclusion

This project demonstrated the practical use of Wireshark for analysing network traffic within a controlled laboratory environment. Capturing and filtering ARP and ICMP traffic provided valuable insight into normal network communication and strengthened practical skills in packet analysis, protocol interpretation, and network monitoring.

The techniques demonstrated in this project form an important foundation for incident detection, digital forensics, intrusion detection, and cybersecurity investigations.
