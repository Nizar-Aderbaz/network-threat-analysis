🔹 Overview

Case-001: Nemotodes Health Network Traffic Analysis (2024-11-26)

This repository contains a comprehensive analysis of a network traffic capture (PCAP) from a medical research facility specializing in nematodes. The analysis focuses on identifying indicators of compromise (IOCs), understanding attack vectors, and documenting the incident for further investigation.

🔹 Incident Background

Date of Incident: November 26, 2024

Facility: Nematodes Health Research Facility

Network Segment: 10.11.26.0/24

Domain: nemotodes.health

Active Directory Domain Controller: 10.11.26.3 (NEMOTODES-DC)

Gateway: 10.11.26.1

🔹 Objectives

Analyze the provided PCAP file to identify malicious activities.

Extract and document IOCs such as IP addresses, domains, and URLs.

Provide a structured incident report detailing findings and recommendations.

🔹 Tools & Resources

Wireshark: For packet capture and analysis.

VirusTotal: For file and URL reputation checks.

AbuseIPDB: For IP address reputation checks.

🔹 Key Findings

Victim Details: Hostname: oboomwald, IP: 10.11.26.183

Attack Indicators:

Kerberos AS-REQ: Authentication Service Request indicating potential credential theft.

DNS Requests: Queries to suspicious domains such as modandcrackedapk.com and classicgrand.com.

TLS Traffic: Encrypted communication with potential command-and-control (C2) server.

Malicious Payload: Evidence of a remote access trojan (RAT) being downloaded.

🔹 Recommendations

Immediate Actions:

Isolate the affected host (10.11.26.183) from the network.

Perform a full malware scan and forensic analysis on the compromised system.

Preventive Measures:

Implement strict DNS filtering to block access to known malicious domains.

Enhance monitoring for unusual Kerberos authentication requests.

Educate staff on recognizing phishing attempts and suspicious activities.
