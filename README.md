# 🛡️ VMware Home Cybersecurity Lab

A personal cybersecurity home lab built with VMware Workstation for hands-on practice in network security, vulnerability assessment, and ethical hacking.

**Student:**  Chandler Yeardly  
**Course:** Cybersecurity & Digital Forensics – Edinburgh College  
**Date:** July 2026

---

## 🎯 Project Objective

To build a safe, isolated virtual environment that simulates a small company network. This lab allows me to practice network scanning, system hardening, vulnerability identification, safe ethical hacking, and basic digital forensics.

---

## 🖥️ Lab Architecture

- **Kali Linux** – Attacker / Security tools machine
- **Metasploitable 2** – Intentionally vulnerable target machine
- **Ubuntu-Secure** – Hardened workstation

**Networking:** NAT + Host-only adapters for internet access and internal communication.

---

## ✅ Key Activities & Findings

### 1. Network Scanning & Reconnaissance
Performed multiple Nmap scans to identify open ports and services on the target machine. Discovered several vulnerable services running on Metasploitable 2.

**Screenshots:** Nmap scans (basic, aggressive, and vulnerability scripts)

### 2. Vulnerability Identification & Web Access
Successfully accessed the Metasploitable web interface and identified vulnerable web applications such as DVWA.

**Screenshots:** Web interface and DVWA login page

### 3. System Hardening
Hardened the Ubuntu-Secure machine by enabling UFW firewall and configuring SSH.

**Screenshots:** UFW status

### 4. Safe Ethical Hacking
Gained SSH access to the vulnerable machine and explored the filesystem. Attempted basic SQL injection on DVWA.

### 5. Basic Digital Forensics
Created a file with sensitive data on Metasploitable, deleted it, and attempted recovery using the `strings` command on Kali. While full recovery was not achieved on the live system, string fragments were identified.

**Screenshots:** File creation/deletion commands and recovery attempt

---

## 📚 What I Learned

- The effectiveness of different Nmap scan types for reconnaissance
- How outdated and default-configured systems are easily exploitable
- The importance of proper system hardening
- Basic concepts of digital forensics and the challenges of recovering deleted data on live systems

---

## 🚀 Future Improvements

- Advanced exploitation using Metasploit Framework
- Full disk imaging and analysis with Autopsy
- Implementation of a SIEM tool (e.g. Wazuh)

---

**Last Updated:** July 1, 2026

*All activities were performed in an isolated educational lab environment.*
