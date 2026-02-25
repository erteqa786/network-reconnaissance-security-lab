# 🔐 Network Reconnaissance & Security Lab

## 📌 Project Overview

This project demonstrates a structured internal network security assessment conducted in a controlled lab environment using Kali Linux (attacker) and Ubuntu 24.04 (target) within Oracle VirtualBox.

The objective was to:

- Discover live hosts in a subnet
- Identify open ports
- Enumerate running services and versions
- Perform basic vulnerability scanning
- Configure and validate firewall rules
- Verify web server exposure

⚠️ This lab was conducted for educational purposes only.

---

## 🧰 Tools & Technologies Used

- Kali Linux
- Ubuntu 24.04
- Nmap
- UFW (Uncomplicated Firewall)
- Apache2
- Oracle VirtualBox

---

## 🖥 Lab Environment

| Component | Description |
|------------|-------------|
| Attacker Machine | Kali Linux |
| Target Machine | Ubuntu 24.04 |
| Network Type | VirtualBox Host-Only |
| Subnet | 192.168.56.0/24 |

---

# 🔎 1️⃣ Host Discovery

Identified active hosts within the subnet.

# 🌐 2️⃣ Connectivity Verification

Verified that the target host responds to ICMP requests.

# 🔍 3️⃣ Port Scanning

Performed a basic TCP port scan to identify open services.

# 🧠 4️⃣ Service & Version Detection

Enumerated running services and identified software versions.

# 🛡 5️⃣ Vulnerability Scanning (NSE Scripts)

Executed Nmap vulnerability scripts against the target.

# 🔥 6️⃣ Firewall Configuration & Validation

Configured UFW firewall rules on Ubuntu target.

sudo ufw allow ssh
sudo ufw allow http
sudo ufw enable
sudo ufw status

# 🌍 7️⃣ Web Server Verification

Verified Apache2 web server exposure from the attacker machine.

🎯 Key Learnings

Subnet-based host discovery

TCP port enumeration

Service fingerprinting

Vulnerability scanning using NSE

Firewall configuration and rule validation

Web service exposure analysis

Understanding filtered vs open ports

📈 Skills Demonstrated

Network Security Fundamentals

Enumeration & Reconnaissance

Linux Command-Line Proficiency

Defensive Security (Firewall Hardening)

Structured Security Documentation

🚀 Future Improvements

Full port scan using -p-

OS detection comparison analysis

Packet capture analysis using Wireshark

Integration with vulnerability scanners like OpenVAS
