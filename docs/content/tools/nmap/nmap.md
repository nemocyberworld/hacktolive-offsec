
# 📘 Master Nmap & Network Enumeration — Full Course Content

## 1. Networking Fundamentals

* What is Nmap
* What is Port Scanning
* Port Scanning Techniques
* 7 Layers of the OSI Model
* TCP/IP Basics & Complete 3-Way Handshake
* Analyzing Network Layer using Wireshark
* Network Discovery

---

## 2. Nmap Basics

* Installing and Running Nmap
* Difference: TCP Connect Scan (`-sT`) vs SYN Scan (`-sS`)
* Port Specification and Scan Order
* TCP & UDP Port Scanning
* Scanning Linux-Based Machines
* Nmap Scan Techniques:
  * SYN (`-sS`)
  * TCP Connect (`-sT`)
  * ACK (`-sA`)
  * Window (`-sW`)
  * Maimon (`-sM`)

---

## 3. Host Discovery

* Ping Scan (`-sn`)
* ARP Scanning on LAN
* ICMP Echo, Timestamp, and Netmask Discovery
* Traceroute with Nmap
* DNS Resolution & Subdomain Discovery
* IPv6 Scanning (`-6`)

---

## 4. Service & OS Detection

* TCP Headers Review
* Service Version Detection (`-sV`)
* OS Detection (`-O`)
* Aggressive Scan (`-A`) — combines OS + Version + Traceroute + NSE
* UDP Range Scans
* Result Diagnosis and Reliability
* Nmap Output and Verbosity Levels (`-v`, `-vv`)

---

## 5. Firewall / IDS Evasion

* Null Scan (`-sN`)
* FIN Scan (`-sF`)
* Xmas Scan (`-sX`)
* Packet Fragmentation (`-f`, `--mtu`)
* Decoy Scans / IP Spoofing (`-D`)
* MAC Spoofing, IP Spoofing, Proxies
* Source Port Manipulation (`--source-port`)
* Data Length Manipulation (`--data-length`)
* Bad Checksums / Bogus TCP Flags
* Timing Templates (`-T0` to `-T5`)
* Scan Delay and Host Timeout (`--scan-delay`, `--host-timeout`)
* Detecting Firewalls & IDS

---

## 6. Nmap Scripting Engine (NSE)

* Introduction to NSE
* Script Categories:
  * **Auth** (default creds, weak login detection)
  * **Brute** (dictionary attacks)
  * **Vuln** (known CVE checks)
  * **Exploit** (direct exploitation)
  * **Discovery** (extra information gathering)
* Running NSE scripts (`--script`)
* Updating NSE Script Database
* Writing Custom NSE Scripts (Lua basics)

---

## 7. Advanced Enumeration with Nmap

* Banner Grabbing
* WHOIS Lookup
* Subdomain Bruteforce
* Finding Hidden Directories
* Detecting Web Application Firewalls (WAF)
* MySQL Enumeration
* Other Database Enumeration (PostgreSQL, MongoDB)
* Nmap for SSL/TLS Enumeration

---

## 8. Output, Automation & Integration

* Exporting Results in Different Formats (`-oN`, `-oX`, `-oG`, `-oA`)
* Using Nmap with Python (python-nmap, libnmap)
* Automating Scans with Bash & Python Scripts
* Integrating Nmap with Metasploit
* Nmap + WebMap for Visual Reports
* Nmap + Faraday / Nessus / OpenVAS for Enterprise Use

---

## 9. Enumeration & Exploitation of Services

* FTP Enumeration & Exploitation
* SSH Enumeration & Exploitation (Hydra, MSFconsole)
* Telnet Enumeration & Exploitation
* SMTP Enumeration & Exploitation
* HTTP (Port 80) Enumeration & Exploitation
* NetBIOS Enumeration & Exploitation
* Rexec Enumeration & Exploitation
* Java RMI Enumeration & Exploitation
* MySQL Enumeration & Exploitation
* PostgreSQL Enumeration & Exploitation
* VNC Enumeration & Exploitation
* X11 Enumeration & Exploitation
* Apache Tomcat Enumeration & Exploitation
* Exploiting Ruby DRB Vulnerability

---

## 10. Real-World Applications of Nmap

* Vulnerability Scanning with NSE
* Using Nmap for Web Security Assessments
* Nmap for IoT/SCADA Devices (Modbus, BACnet, SNMP)
* Enterprise-Scale Network Scanning (`--min-hostgroup`, `--min-parallelism`)
* Combining Nmap with Other Offensive Security Tools
* Case Studies: Nmap in Red Teaming & Pentests

---

## 11. Reporting & Documentation

* Generating Nmap Reports for Clients/Organizations
* Exporting Scans into HTML/Dashboards
* Installing and Using WebMap for Visualization
* Writing Professional Reports with Nmap Data

---

✅ Now it’s  **exhaustive** : everything from **fundamentals → advanced scanning → NSE → firewall evasion → exploitation → enterprise-scale automation → reporting** is covered.

Would you like me to also **format this into a professional syllabus PDF with tables & sections** (so you can directly use it in class/training)?
