# 🛡️ VMware Home Cybersecurity Lab

A personal cybersecurity home lab built with **VMware Workstation** for hands-on learning in network security, vulnerability assessment, and digital forensics.

**Project Status:** In progress 
**Date:** June 2026  
**Student:** Chandler Yeardly — Cybersecurity & Digital Forensics at Edinburgh College

---

## 🎯 Project Objective

To build a safe, isolated virtual environment that simulates a small company network. This lab allows me to practice:
- Network scanning and reconnaissance
- System hardening
- Vulnerability identification
- Safe ethical hacking techniques
- Digital forensics preparation

---

## 🖥️ Lab Architecture

### Virtual Machines

| Machine          | Role                        | OS                  | RAM    | IP Address (example) |
|------------------|-----------------------------|---------------------|--------|----------------------|
| Kali-Lab         | Attacker / Security Tool    | Kali Linux          | 4 GB   | 192.168.182.133      |
| Metasploitable   | Vulnerable Target           | Linux (Ubuntu-based)| 1 GB   | 192.168.182.136      |
| Ubuntu-Secure    | Hardened Workstation        | Ubuntu Desktop      | 3 GB   | 192.168.182.135      |

### Network Configuration
- **NAT Adapter**: Provides internet access (isolated from real network)
- **Host-only Adapter**: Allows VMs to communicate with each other (internal lab network)

---

## 🛠️ Tools & Technologies Used

- **Virtualization**: VMware Workstation Player
- **Operating Systems**: Kali Linux, Ubuntu Desktop, Metasploitable 2
- **Scanning**: Nmap
- **Analysis**: Wireshark (to be added), tcpdump
- **Hardening**: UFW Firewall, system updates
- **Documentation**: GitHub, Markdown, Screenshots

---

## 📋 Setup Instructions

### 1. Install VMware Workstation Player
- Downloaded from official VMware website
- Created Host-only virtual network

### 2. Virtual Machines Created
- Imported/Installed Kali Linux
- Imported Metasploitable 2 (vulnerable lab target)
- Installed fresh Ubuntu Desktop

### 3. Network Setup
- Configured NAT + Host-only adapters on all VMs
- Verified connectivity between machines

### 4. Basic Hardening (Ubuntu-Secure)

### Screenshots
