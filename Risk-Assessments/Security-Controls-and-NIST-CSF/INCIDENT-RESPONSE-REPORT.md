# Incident Response Report

## Incident Overview

**Incident Name:** ICMP Network Scan Detection

**Incident Type:** Reconnaissance / Network Scanning

**Date:** Simulated Lab Exercise

**Detection Method:**

- Snort Intrusion Detection System (IDS)
- Wireshark Traffic Analysis
- Syslog Monitoring

**Systems Affected**

- Enterprise Router
- Internal LAN
- IDS Monitoring Server

---

# Executive Summary

This report documents the response to a simulated network reconnaissance incident detected during a cybersecurity laboratory. An ICMP network scan triggered a Snort IDS alert, indicating potential reconnaissance activity against the enterprise network.

The incident was investigated using the PICERL Incident Response methodology. Monitoring tools including Snort, Wireshark, and Syslog were used to detect, analyse, contain, and verify the incident. The response successfully prevented further suspicious activity and confirmed that all systems remained operational.

---

# PICERL Incident Response

## Preparation

Before the incident occurred, several security controls had already been implemented:

- VLAN segmentation
- SSH Version 2 for secure administration
- Syslog monitoring
- Snort Intrusion Detection System
- Wireshark packet analysis
- Extended ACLs
- Device hardening

These controls provided visibility into network activity and allowed suspicious traffic to be detected quickly.

---

## Identification

The incident was identified when Snort generated an alert indicating ICMP traffic on the network.

Further investigation using Wireshark confirmed that ICMP packets were being transmitted as part of a network scanning activity.

Syslog logs were reviewed to verify that no additional security events occurred during the incident.

---

## Containment

To prevent further reconnaissance activity, the ICMP traffic was stopped.

The network was monitored to confirm that no additional ICMP alerts were generated after containment.

Monitoring continued using:

- Snort IDS
- Syslog
- Wireshark

---

## Eradication

Analysis determined that the detected traffic originated from the simulated laboratory exercise.

No malware or unauthorised device was discovered on the network.

After confirming the source of the traffic, no further remediation actions were required.

---

## Recovery

Once monitoring confirmed that the ICMP activity had ceased, the network was assessed to ensure normal operation.

Verification included:

- Successful network connectivity
- No additional IDS alerts
- Normal Syslog activity
- Normal router and switch operation

The enterprise network was returned to normal operational status.

---

## Lessons Learned

The incident demonstrated the importance of layered security controls.

Key lessons included:

- Continuous monitoring enables rapid detection of suspicious activity.
- IDS alerts should always be verified using packet analysis.
- Multiple monitoring tools provide stronger visibility than relying on a single security control.
- Incident response procedures reduce response time and improve operational resilience.

---

# Incident Timeline

| Time | Event |
|-------|-------|
| 10:30 | ICMP traffic triggered a Snort IDS alert. |
| 10:33 | Traffic was analysed using Wireshark and confirmed as ICMP network scanning activity. |
| 10:35 | ICMP traffic was terminated and monitoring continued to verify that no further suspicious activity occurred. |
| 10:40 | Network services were verified as operational and the incident investigation was concluded. |

---

# Recommendations

The following recommendations are based on the findings from this simulated incident:

1. Continue monitoring network traffic using Snort IDS and Syslog.
2. Maintain secure remote administration through SSH.
3. Perform regular incident response exercises using the PICERL methodology.
4. Review IDS signatures and detection rules regularly.
5. Conduct periodic network traffic analysis using Wireshark.
6. Maintain VLAN segmentation and access control policies.
7. Keep network devices updated with the latest security patches.
8. Document all security incidents for future analysis and continuous improvement.

---

# Technologies Used

- Cisco Packet Tracer
- Snort IDS
- Wireshark
- Syslog
- Cisco IOS
- SSH Version 2
- VLAN Segmentation
- Extended Access Control Lists (ACLs)

---

# Skills Demonstrated

- Incident Response
- Network Traffic Analysis
- Intrusion Detection
- Security Monitoring
- Threat Identification
- Network Defence
- Cybersecurity Documentation
- Enterprise Network Security

---

# References

- NIST Cybersecurity Framework (CSF)
- Cisco Networking Academy
- MITRE ATT&CK Framework
- ISO/IEC 27001
- Protection of Personal Information Act (POPIA)
- Cybercrimes Act 19 of 2020
