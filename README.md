# Network Scanning and Enumeration using Nmap

## Project Overview
This project demonstrates network scanning and enumeration using Nmap in a controlled lab environment. Kali Linux was used as the attacking machine and Metasploitable 2 as the target machine. The project focuses on identifying active hosts, open ports, running services, operating system details, and basic vulnerability information.

## Tools Used
- Kali Linux
- Metasploitable 2
- Nmap
- VirtualBox

## Objectives
- Discover active hosts on the network.
- Identify open TCP and UDP ports.
- Detect running services and service versions.
- Perform OS fingerprinting.
- Execute Nmap Scripting Engine (NSE) scripts.
- Generate and analyze network scan reports.

## Commands Used

```bash
ip a
ifconfig
ping 192.168.56.102
nmap -sn 192.168.56.0/24
nmap 192.168.56.102
sudo nmap -sS 192.168.56.102
sudo nmap -sU 192.168.56.102
nmap -sV 192.168.56.102
sudo nmap -O 192.168.56.102
sudo nmap -A 192.168.56.102
nmap -sC 192.168.56.102
nmap --script vuln 192.168.56.102
nmap -A 192.168.56.102 -oN scan_results.txt
```

## Results
- Verified network connectivity between Kali Linux and Metasploitable 2.
- Discovered active hosts using host discovery.
- Identified multiple open ports and running services.
- Detected service versions and operating system details.
- Executed NSE scripts for additional service information.
- Generated and saved scan reports.

## Conclusion
This project provided practical experience in network reconnaissance and enumeration using Nmap. It improved my understanding of host discovery, port scanning, service detection, operating system fingerprinting, NSE scripts, and scan report generation.
