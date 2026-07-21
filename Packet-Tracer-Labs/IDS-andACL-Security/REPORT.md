# IDS and ACL Security

## Executive Summary

This project demonstrates the implementation of multiple network security controls within a controlled CyberLab environment. The primary objective was to configure an Intrusion Detection System (IDS) using Snort to detect ICMP traffic while validating network access restrictions using Extended Access Control Lists (ACLs).

A custom Snort detection rule was created to monitor ICMP packets, and generated alerts confirmed successful detection of network activity. Extended ACLs were also configured within a Cisco Packet Tracer network to restrict unauthorized communication and verify traffic filtering. The project illustrates how detection and prevention mechanisms complement one another in enterprise network security.

---

# Objectives

The objectives of this project were to:

- Configure Snort as an Intrusion Detection System.
- Create and implement a custom Snort rule.
- Detect ICMP network traffic.
- Analyse generated IDS alerts.
- Configure Extended Access Control Lists.
- Validate network traffic filtering.
- Demonstrate layered network security controls.

---

# Scope

This project was performed within a virtual CyberLab consisting of Kali Linux, Snort IDS, Oracle VirtualBox, and Cisco Packet Tracer.

The investigation focused on monitoring ICMP traffic using Snort and validating network access restrictions using Extended ACLs. All testing was conducted within an isolated laboratory environment.

---

# Lab Environment

| Component | Description |
|-----------|-------------|
| Operating System | Kali Linux |
| IDS Software | Snort |
| Virtualisation Platform | Oracle VirtualBox |
| Network Simulator | Cisco Packet Tracer |
| Detection Method | Signature-Based IDS |
| Security Control | Extended Access Control Lists |

---

# Methodology

The project followed the following process:

1. Configure the CyberLab environment.
2. Install and configure Snort.
3. Create a custom Snort rule to detect ICMP traffic.
4. Generate ICMP traffic between hosts.
5. Observe and verify generated IDS alerts.
6. Configure Extended ACLs within Cisco Packet Tracer.
7. Validate that unauthorized traffic was successfully blocked.
8. Document observations and security findings.

---

# Snort Configuration

Snort was configured to inspect network traffic using a custom detection rule designed to identify ICMP Echo Request packets.

Successful execution of the rule demonstrated that Snort was correctly monitoring network activity and generating alerts whenever matching traffic was detected.

The generated alerts verified the effectiveness of signature-based intrusion detection.

---

# Access Control List Validation

Extended Access Control Lists were configured to regulate communication between network segments.

Traffic testing confirmed that authorized communication continued normally while restricted traffic was successfully denied according to the configured ACL rules.

This demonstrated how ACLs provide preventative security controls by enforcing network access policies.

---

# Findings

The project produced the following results:

- Snort successfully detected ICMP traffic.
- The custom IDS rule generated alerts correctly.
- Extended ACLs successfully enforced network access restrictions.
- Traffic monitoring and traffic filtering worked together as complementary security controls.
- Network security controls functioned as expected within the laboratory environment.

---

# Security Recommendations

Based on the implementation and testing performed, the following recommendations are made:

- Regularly review and update Snort rule sets to detect emerging threats.
- Monitor IDS alerts continuously for suspicious activity.
- Periodically audit ACL configurations to ensure compliance with security policies.
- Apply the principle of least privilege when designing ACL rules.
- Combine intrusion detection with preventative controls to strengthen overall network security.

---

# Conclusion

This project successfully demonstrated the implementation of both detective and preventative security controls within a controlled CyberLab environment.

Snort effectively detected ICMP traffic using a custom signature, while Extended Access Control Lists successfully restricted unauthorized communication. Together, these technologies illustrate the importance of layered defence in modern enterprise networks.

The practical experience gained through this project strengthened skills in intrusion detection, signature creation, network monitoring, traffic filtering, and security control validation. These competencies form an essential foundation for Security Operations Centre (SOC), Cybersecurity Analyst, and Network Security roles.
