# 🛡️ VMware Home Cybersecurity Lab

A personal cybersecurity home lab built with VMware Workstation for hands-on practice in network security, vulnerability assessment, and ethical hacking.

**Student:** [Your Full Name]  
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

**Networking:** NAT + Host-only adapters

---

## ✅ Key Activities & Screenshots

### 1. Network Scanning & Reconnaissance
Performed multiple Nmap scans to identify open ports and services.

![Nmap Metasploitable2 Scan](screenshots/04-nmap-metasploitable2-scan.png)
![Nmap Port Scan](screenshots/05-nmap-port-scan.png)
![Nmap Aggressive Scan](screenshots/06-nmap-aggressive-scan.png)
![Nmap Vulnerability Scan](screenshots/07-nmap-vulnerability-scan.png)

### 2. Vulnerability Identification, Web Access & SQL Injection
Accessed the Metasploitable web interface and vulnerable applications.

![Metasploitable Web Interface](screenshots/08-metasploitable-web-interface.png)
![DVWA Login](screenshots/09-dvwa-login.png)
![SQL Injection Attempt](screenshots/14-sql-injection.png)

### 3. System Hardening
Enabled UFW firewall on Ubuntu-Secure.

![UFW Firewall Status](screenshots/10-ufw-status.png)

### 4. Safe Ethical Hacking & Forensics
Gained SSH access to Metasploitable. Created, deleted, and attempted to recover sensitive data using `strings` command.

![SSH Access](screenshots/11-ssh-login.png)
![File Creating & Deletion](screenshots/17-create-remove-files.png)
![Snapshots Created](screenshots/15-snapshot-before-forensics.png)
![File Recovery](screenshots/16-file-recovery.png)

---

## 📚 What I Learned

- The power of reconnaissance with Nmap
- How easily vulnerable systems can be accessed
- Importance of system hardening
- Basic digital forensics concepts and challenges of data recovery

---

## 🚀 Future Improvements

- Advanced exploitation with Metasploit
- Full disk imaging with Autopsy
- SIEM implementation

---

**Last Updated:** July 1, 2026

*All activities performed in an isolated educational lab environment.*
