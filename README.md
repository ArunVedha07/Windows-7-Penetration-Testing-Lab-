# Windows 7 MS17-010 (EternalBlue) Exploitation

This repository documents the assessment and exploitation of the **MS17-010 (CVE-2017-0143)** vulnerability on a Windows 7 target. The objective was to identify SMB-related weaknesses, validate the EternalBlue vulnerability, and achieve remote code execution using Metasploit.

## Summary of Actions
- Performed network and service enumeration with Nmap  
- Identified SMBv1 exposure and confirmed MS17-010 vulnerability  
- Executed the EternalBlue exploit via Metasploit  
- Established a remote VNC session upon successful compromise

## Repository Structure
- **/report** — Detailed exploitation report (PDF)  
- **/screenshots** — Evidence collected during each phase  
- **/notes** — Commands and reference material used during the assessment  

## Tools & Technologies
- Kali Linux  
- Nmap + NSE scripts  
- Metasploit Framework  
- VirtualBox test environment  

## Purpose
This project was conducted strictly for **educational and authorized penetration testing practice**.
