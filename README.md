# SentinelShield – Advanced Intrusion Detection & Web Protection System

SentinelShield is a cybersecurity project designed to demonstrate how Intrusion Detection Systems (IDS) and Web Application Firewalls (WAF) detect, monitor, and block malicious web traffic in real-time using Kali Linux and Python-based security tools.

## 🚀 Features

* Web request inspection and monitoring
* SQL Injection & XSS attack detection
* ModSecurity WAF configuration
* OWASP Core Rule Set integration
* DVWA vulnerability testing environment
* OpenVAS vulnerability scanning
* Security log analysis and alert generation

## 🛠️ Technologies Used

* Python3
* Kali Linux
* ModSecurity
* OWASP CRS
* DVWA
* OpenVAS / Greenbone
* Apache2
* MariaDB

## ⚙️ Project Workflow

1. Configure ModSecurity WAF
2. Enable OWASP Core Rule Set
3. Setup DVWA vulnerable lab
4. Simulate HTTP attacks
5. Monitor logs & alerts
6. Perform vulnerability scanning
7. Generate security reports

## ▶️ Installation

```bash
sudo apt update
sudo apt install libapache2-mod-security2 -y
sudo apt install gvm -y
```

## 🔍 Testing Example

```bash
curl http://127.0.0.1/DVWA/login.php?exec=/bin/bash
```

## 📊 Learning Outcomes

* Understanding IDS/WAF architecture
* HTTP traffic analysis
* Web attack detection techniques
* Security monitoring & logging
* Vulnerability assessment using OpenVAS

## ⚠️ Disclaimer

This project is developed strictly for educational and ethical cybersecurity learning purposes only. Use only in authorized lab environments.

## 👩‍💻 Author

**Sakshi Maruti Nalawade**
Institute: Unified Mentor
