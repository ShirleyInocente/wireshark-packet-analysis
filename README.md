# Wireshark Packet Analysis Investigation

## Overview

This project documents a structured network traffic investigation performed using Wireshark to analyze a packet capture (PCAP). The objective was to determine whether the captured network activity contained indicators of compromise (IoCs), suspicious behavior, or evidence of malicious activity.

The investigation followed a methodical analysis process that included establishing a network traffic baseline, examining key protocols, performing packet-level inspection, and validating suspicious indicators using external threat intelligence resources.

## Investigation Objectives

- Analyze the packet capture (referred to Task #1003) using Wireshark.
- Establish a baseline of network traffic and protocol distribution.
- Examine DNS, TLS, QUIC, SMB, and HTTP communications.
- Identify potential indicators of compromise (IoCs) and suspicious network behavior.
- Validate suspicious findings using VirusTotal.
- Document findings and provide security recommendations.

## Tools Used

- Wireshark
- VirusTotal
- Packet Capture (PCAP) Analysis
- Network Protocol Analysis

## Investigation Methodology

The investigation followed a structured workflow:

1. Loaded and verified the packet capture.
2. Established a baseline using Protocol Hierarchy Statistics.
3. Analyzed DNS, TLS, QUIC, SMB, and HTTP traffic.
4. Performed packet-level inspection of suspicious activity.
5. Validated findings using VirusTotal.
6. Documented observations, conclusions, and security recommendations.

## Protocols Analyzed

- DNS
- TLS
- QUIC
- SMB
- HTTP

## Key Findings

The investigation found no confirmed indicators of compromise or malicious network activity.

Key observations included:

- Network traffic was consistent with expected application behavior.
- DNS activity reflected legitimate domain resolution.
- TLS and QUIC communications were consistent with normal encrypted traffic.
- SMB activity showed expected internal file-sharing behavior.
- HTTP traffic did not reveal suspicious requests or unauthorized data transfers.
- A DNS domain that initially appeared suspicious was validated through VirusTotal and determined to be associated with legitimate services.

## Skills Demonstrated

- Network Traffic Analysis
- Packet Analysis
- Protocol Analysis
- Threat Intelligence Validation
- Security Documentation
- Technical Report Writing
- Evidence-Based Investigation

## Project Files

- **Investigation Report:** `Wireshark_Packet_Analysis_Report.pdf`
- **Presentation:** `Wireshark_Analysis_Presentation.pdf`

## About Me

I am a CompTIA Security+ and Splunk Core Certified cybersecurity professional with hands-on experience in network traffic analysis, security operations, and threat detection. I enjoy investigating network activity, documenting findings, and continuing to develop practical cybersecurity skills through hands-on projects.

**LinkedIn:** [Shirley Inocenté](https://www.linkedin.com/in/sinocente/)

---

Thank you for taking the time to review this project. Feedback is always welcome as I continue building my cybersecurity portfolio.
