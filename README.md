# Nmap Lab

## Overview
This lab contains different Nmap scans on legal targets (`scanme.nmap.org`) and localhost.  
It demonstrates aggressive scanning, OS detection, service/version detection, and NSE script execution.

## Tools
- Kali Linux
- Zenmap (GUI)
- Nmap CLI

## Scans

### 1. Aggressive Scan
Command: `nmap -A scanme.nmap.org`  
![Aggressive Scan](nmap-lab/screenshots/aggressive-scan.png)

### 2. OS Detection Scan
Command: `nmap -O scanme.nmap.org`  
![OS Scan](nmap-lab/screenshots/os-scan.png)

### 3. NSE Script Scan
Command: `nmap -sC scanme.nmap.org`  
![NSE Scan](nmap-lab/screenshots/nse-scan.png)

### 4. Service & Version Scan (Remote)
Command: `nmap -sV scanme.nmap.org`  
![Service Scan Remote](nmap-lab/screenshots/sv-scan-remote.png)

### 5. Service & Version Scan (Localhost)
Command: `nmap -sV localhost`  
![Service Scan Localhost](nmap-lab/screenshots/sv-scan-localhost.png)

---

### Notes
- All screenshots are inside the `nmap-lab/screenshots/` folder.  
- Optional: full outputs can be saved in `nmap-lab/outputs/`.
