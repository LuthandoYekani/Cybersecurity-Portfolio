# 🌐 Network Traffic Analysis using Wireshark

## 📖 Project Overview

This project demonstrates the use of **Wireshark** to capture, filter and analyse network traffic within a controlled CyberLab environment. The analysis focused on identifying common network protocols, understanding packet behaviour and interpreting captured traffic to determine its security significance.

Packet captures were analysed using Wireshark display filters to isolate specific protocols, allowing detailed inspection of network communications between hosts.

---

## 🎯 Objectives

- Capture live network traffic using Wireshark
- Apply display filters to isolate specific protocols
- Analyse ARP and ICMP packets
- Interpret packet contents and communication behaviour
- Identify potential security implications
- Develop practical packet analysis skills used by Cybersecurity Analysts

---

## 🛠 Technologies Used

- Wireshark
- Kali Linux
- Ubuntu Linux
- Oracle VirtualBox
- Internal Virtual Network

---

## 🖥️ Lab Environment

The packet capture was performed within an isolated CyberLab environment consisting of a Kali Linux virtual machine acting as the monitoring workstation and an Ubuntu virtual machine generating network traffic.

Using an isolated laboratory environment ensured that all captured traffic remained controlled and could be analysed without affecting external systems.

---

## 📡 Packet Capture

Network traffic was captured using Wireshark running on a Kali Linux virtual machine connected to an isolated CyberLab environment. Packet captures were collected while communication occurred between the Kali Linux monitoring system and an Ubuntu virtual machine.

Traffic was captured in real time before applying display filters to isolate specific protocols for detailed analysis.

---

## 🔍 Display Filters Used

The following Wireshark display filters were applied during the investigation:

| Display Filter | Purpose |
|---------------|---------|
| `arp` | Display only Address Resolution Protocol traffic |
| `icmp` | Display only Internet Control Message Protocol traffic |

These filters simplified packet analysis by removing unrelated traffic and allowing individual protocols to be examined independently.

---

## 🖼️ Packet Analysis Evidence

### ARP Traffic Analysis

![ARP Filter](images/Wireshark-ARP-Filter-Applied.png)

The ARP display filter was used to isolate Address Resolution Protocol traffic. The captured packets showed devices requesting and responding with MAC address information required before communication could occur on the local network.

---

### ICMP Traffic Analysis

![ICMP Filter](images/Wireshark-ICMP-Filter-Applied.png)

The ICMP display filter isolated Echo Requests and Echo Replies generated during connectivity testing. The captured packets confirmed successful communication between hosts and demonstrated how ICMP is commonly used for network troubleshooting and reachability testing.

---

## 📊 Traffic Analysis Findings

Analysis of the captured network traffic revealed the following:

- ARP requests and replies were successfully exchanged between hosts to resolve MAC addresses before communication.
- ICMP Echo Requests and Echo Replies confirmed successful network connectivity between the Kali Linux monitoring system and the Ubuntu virtual machine.
- Applying protocol-specific display filters significantly reduced unrelated traffic, making packet analysis more efficient.
- No malicious or abnormal network behaviour was observed during the controlled laboratory exercise.

---

## 🚨 Security Implications

Although the captured traffic was generated within a controlled CyberLab environment, the analysis demonstrated several important cybersecurity concepts:

- ARP traffic can be monitored to detect suspicious behaviour such as ARP spoofing or cache poisoning attacks.
- ICMP traffic can reveal host discovery and network reconnaissance attempts when used excessively.
- Packet analysis enables security analysts to investigate communication patterns, verify connectivity, and identify indicators of compromise.
- Wireshark provides valuable visibility into network activity, supporting both incident investigations and routine network monitoring.

---

## 🧠 Skills Demonstrated

- Network packet capture using Wireshark
- Packet filtering using display filters
- ARP protocol analysis
- ICMP protocol analysis
- Network traffic investigation
- Packet interpretation
- Cybersecurity monitoring
- Network troubleshooting
- Technical documentation

---

## 📁 Project Files

| File | Description |
|------|-------------|
| README.md | Project overview and technical documentation |
| REPORT.md | Detailed technical report |
| images/ | Wireshark screenshots used during analysis |
| captures/ | Packet capture files (PCAP) |
| findings/ | Analysis notes and supporting documentation |

---

## 🎓 Lessons Learned

This project strengthened my understanding of how network communication occurs at the packet level and demonstrated the importance of packet analysis in cybersecurity operations. Working with Wireshark improved my ability to isolate specific protocols, interpret captured traffic, and understand how security analysts investigate network communications during troubleshooting and incident response.

The practical experience gained through this laboratory exercise provides a strong foundation for more advanced network analysis, intrusion detection, and digital forensics activities.
