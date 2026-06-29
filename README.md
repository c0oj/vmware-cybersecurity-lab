# 🛡️ VMware Home Cybersecurity Lab

A personal cybersecurity home lab built with VMware Workstation for hands-on practice in network security, vulnerability assessment, and ethical hacking.

**Student:** Chandler Yeardly 
**Course:** Cybersecurity & Digital Forensics – Edinburgh College  
**Date:** June 2026

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

- **Kali Linux** – Attacker / Security tools machine
- **Metasploitable 2** – Intentionally vulnerable target machine
- **Ubuntu-Secure** – Hardened workstation

**Networking:** NAT + Host-only adapters

---

## ✅ Completed Activities

### Phase 1–3: Lab Setup & Hardening
- Created and configured 3 VMs in VMware
- Configured proper networking
- Hardened Ubuntu-Secure with UFW firewall and SSH

### Phase 4: Vulnerability Identification
- Performed detailed Nmap scans on Metasploitable
- Discovered multiple vulnerable services
- Accessed the Metasploitable web interface

### Screenshots Taken

**Folder:** `/screenshots`

- `01-vmware-library.png` – All VMs running
- `02-nmap-scans.png` – Nmap scan results
- `03-metasploitable-web-interface.png` – Main web page
- `04-dvwa-login.png` – DVWA or other web apps (if taken)
- `05-ufw-status.png` – Firewall status on Ubuntu
- `06-other-scans.png` – Additional screenshots

---

## 🔍 Key Findings

- Multiple services running on Metasploitable with known vulnerabilities
- Web applications (such as DVWA) accessible with default credentials
- Demonstrated difference between hardened Ubuntu and vulnerable Metasploitable

---

## 📚 What I Learned

- How to properly configure isolated lab networking in VMware
- Importance of network scanning using Nmap
- How easily vulnerable machines can be discovered and accessed
- Value of system hardening (firewall, updates, strong credentials)

---

## 🚀 Next Steps (Planned)

- Successfully exploit services on Metasploitable
- Perform basic incident response / forensics
- Add SIEM tool (Wazuh)
- Write full lab report

---

**Last Updated:** June 29, 2026

*All activities performed in an isolated educational lab environment.*
