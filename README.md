# MainCrafts Cyber Security Internship – Task 3

## Vulnerability Scanning & Assessment

This repository contains my **Task 3 submission** for the MainCrafts Technology Cyber Security & Ethical Hacking Internship.

The project focuses on performing network reconnaissance, service enumeration, web server scanning, directory discovery, vulnerability identification, risk assessment, and remediation recommendations in a controlled laboratory environment.

## Objective

The objective of this assessment was to:

- Discover and confirm network assets
- Identify open ports and running services
- Enumerate service versions
- Identify outdated or misconfigured services
- Perform web server security scanning
- Discover accessible directories and paths
- Document security findings
- Assess risks and recommend remediation

## Assessment Environment

**Target:** DVWA (Damn Vulnerable Web Application)

**Target OS:** Ubuntu 24.04.4 LTS

**Target IP:** `192.168.202.138`

**Scanner:** Kali Linux

**Scanner IP:** `192.168.202.129`

**Virtualization:** VMware

**Web Server:** Apache HTTP Server 2.4.58

## Tools Used

- **Nmap** – Network discovery, port scanning and service/version enumeration
- **Nikto** – Web server security scanning
- **Dirsearch** – Directory and file discovery
- **cURL** – Manual HTTP response verification

## Assessment Methodology

The assessment followed this workflow:

```text
Host Discovery
      ↓
Port & Service Enumeration
      ↓
Web Server Scanning
      ↓
Directory Discovery
      ↓
Finding Analysis
      ↓
Risk Rating
      ↓
Remediation Recommendations
