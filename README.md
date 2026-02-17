# Clash-of-Teams-Red-vs-Blue-Lab
Red Team vs Blue Team Simulation using Metasploitable 2 (vsftpd 2.3.4) | Nmap | Metasploit | Log Analysis | Firewall Hardening
# 🔥 Red Team vs Blue Team – Breach & Defend Lab

## 📌 Project Overview
This project demonstrates a real-world cyber attack and defense simulation using Metasploitable 2.

## 🛠 Tools Used
- Nmap
- Metasploit Framework
- Linux Log Analysis
- iptables Firewall

## 🚨 Vulnerability Exploited
vsftpd 2.3.4 Backdoor Vulnerability

## ⚔ Red Team Phase
- Performed Nmap reconnaissance
- Identified vulnerable FTP service
- Exploited using Metasploit
- Gained root shell access

## 🛡 Blue Team Phase
- Analyzed auth.log for suspicious activity
- Identified attacker IP
- Implemented firewall rule
- Verified remediation with Nmap

## 🎯 Outcome
Successfully demonstrated attack lifecycle and mitigation strategy.

---

👨‍💻 Author: Aniket Pawar

# 🔥 Red Team vs Blue Team – Breach & Defend Lab

👨‍💻 Author: Aniket Pawar  

---

## 📌 Project Overview
This project demonstrates a real-world cyber attack and defense simulation using Metasploitable 2.

---

## 🔍 1️⃣ Nmap Reconnaissance

![Nmap Scan](screenshots/nmap_scan.png)

Identified vsftpd 2.3.4 running on port 21.

---

## 💥 2️⃣ Exploitation – Metasploit

![Metasploit Exploit](screenshots/metasploit_exploit.png)

Used exploit/unix/ftp/vsftpd_234_backdoor to gain access.

---

## 👑 3️⃣ Root Access

![Root Shell](screenshots/root_shell.png)

![Root Shell](screenshots/root_shell1.png)

Successfully gained root shell access.

---

## 🛡 4️⃣ Log Detection

![Log Evidence](screenshots/auth_log_evidence.png)

![Log Evidence](screenshots/attacker_ip_detected.png)

Suspicious attacker IP detected in auth.log.

---

## 🚫 5️⃣ Firewall Remediation

![Firewall Rule](screenshots/firewall_rule.png)

Blocked attacker IP using iptables.

---

## 🔎 6️⃣ Validation Scan

![Nmap After Block](screenshots/nmap_after_block.png)

All ports filtered after firewall rule implementation.

---

## 🛠 Tools Used
- Nmap
- Metasploit Framework
- Linux Log Analysis
- iptables Firewall

---

## 🎯 Outcome
Successfully demonstrated full attack lifecycle and defensive mitigation.


