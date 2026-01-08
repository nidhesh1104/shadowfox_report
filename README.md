# ShadowFox Cybersecurity Internship – Lab Report

## Disclaimer
This report is based on **authorized lab environments and simulated targets only**.
No real client data or credentials are disclosed.

## Internship Details
- Company: ShadowFox
- Domain: Cybersecurity
- Level: Beginner – Advanced
- Duration: 1 Month

## Tools Used
- Nmap
- Gobuster
- Wireshark
- Metasploit
- Veracrypt
- enum4linux
- Hydra

## Task 1: Port Scanning
- Objective: Identify open ports
- Tool: Nmap
- Result: HTTP service detected
- Risk Level: Low
- Mitigation: HTTPS enforcement, patching

## Task 2: Directory Enumeration
- Tool: Gobuster
- Finding: Sensitive directories exposed
- Risk: Medium
- Mitigation: Access control, remove repo files

## Task 3: Credential Exposure (Lab)
- Observation: Credentials transmitted in plaintext
- Risk: High
- Mitigation: HTTPS, HSTS, MFA

## Intermediate & Advanced Tasks
- Reverse shell (lab simulation)
- Disk decryption (Veracrypt)
- Privilege escalation (TryHackMe lab)

## Key Learnings
- SOC investigation workflow
- Vulnerability documentation
- Risk scoring (CVSS)
- Incident mitigation
