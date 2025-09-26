# Network Traffic Analysis – Malware Investigation

Analyst: Nizar Aderbaz | Date: September 4th, 2024

## Overview

This project analyzes a network capture (PCAP) from an internal host showing suspicious activity. The focus was on identifying malware behavior, extracting IOCs, and understanding attacker techniques within the network.

## Key Skills Demonstrated

Network Analysis: Filtered and examined traffic using Wireshark to isolate malicious communications.

Malware Investigation: Identified potential C2 and data exfiltration activity.

Threat Intelligence: Cross-checked IOCs with VirusTotal, AbuseIPDB, and ThreatFox.

Documentation & Reporting: Structured findings for professional incident response.

## Highlights

Internal host 172.17.0.99 showed SMB and Kerberos exploitation attempts.

Suspicious HTTP POST requests to 79.124.78.197 confirmed malicious activity (KoiLoader malware).

IOCs included domains, IPs, and URLs linked to malware infrastructure.

## Tools Used

Wireshark | VirusTotal | AbuseIPDB | ThreatFox

## Lessons Learned

Recognizing attacker patterns in network traffic (C2, beaconing, exploitation).

Correlating traffic with threat intelligence to confirm malicious activity.

Producing clear, actionable documentation for incident response.

This repository is for educational purposes and demonstrates practical DFIR skills. Explore the PCAP (if provided) and analyze the traffic following the documented methodology.
