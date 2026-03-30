# 👨‍💻 Cybersecurity Portfolio

## About Me
I am a cybersecurity analyst focused on threat detection, network security, and vulnerability assessment. I have hands-on experience working with security tools, analyzing threats, and conducting security assessments.

---

##  🛠️ Technical Skills

### 🔐 Security Tools
- John the Ripper (Password Cracking & Hash Analysis)
- Aircrack-ng (Wireless Security Testing)
- Sysmon (Endpoint Monitoring & Logging)
- Zphisher / MedusaPhisher (Phishing Simulation)

### 💻 Operating Systems
- Linux (Command Line, Security Testing)
- Windows (System Monitoring, Event Analysis)

### 🧪 Security Domains
- Password Auditing & Cracking
- Wireless Network Security Assessment
- Phishing & Social Engineering Simulation
- Endpoint Detection & Monitoring (Sysmon)
- Security Risk Assessment & IT Auditing

### 📊 Monitoring & Analysis
- Log Analysis (Windows Event Viewer, Sysmon Logs)
- Process & Network Activity Monitoring
- Threat Detection & Basic Incident Analysis

### ⚙️ Tools & Technologies
- PowerShell (Basic Command Execution & Automation)
- Network Packet Capture (Wi-Fi Assessment)
- System Configuration & Security Hardening

### 🧠 Concepts & Knowledge
- CIA Triad (Confidentiality, Integrity, Availability)
- Authentication & Access Control
- Network Security Fundamentals
- Basic Threat Modeling & Risk Analysis

---

## Projects

## 🔐 Cybersecurity Projects

### 1. Password Hash Analysis & Recovery (John the Ripper)

This project demonstrates a controlled password auditing exercise using a dictionary attack to identify weak credentials.

Tools & Environment:
- Tool: John the Ripper
- OS: Linux
- Wordlist: rockyou.txt

Process:
- Prepared password hash file for analysis
- Executed cracking using John the Ripper
- Matched hashes against a wordlist

Result:
- Successfully recovered a weak password from the hash

Key Insight:
Weak passwords are highly vulnerable to dictionary-based attacks, emphasizing the need for strong password policies.

👉 [View Full Report](./password_hash_analysis_john_the_ripper.pdf)

---

### 2. 📡 Wireless Security Assessment (Aircrack-ng)

This project demonstrates a controlled wireless network security assessment using Aircrack-ng to evaluate Wi-Fi security and identify vulnerabilities in weak encryption configurations.

Tools & Environment:
- Tool: Aircrack-ng suite
- OS: Linux
- Mode: Monitor mode enabled wireless adapter

Process:
- Enabled monitor mode on wireless interface
- Captured network packets and WPA/WEP handshake
- Performed password cracking using captured handshake
- Analyzed network security strength

Result:
- Successfully demonstrated how weak Wi-Fi passwords can be compromised

Key Insight:
Wireless networks using weak passwords or outdated encryption (e.g., WEP) are highly vulnerable to unauthorized access.

👉 [View Full Report (PDF)](./wireless_security_assessment_aircrack-ng.pdf)

---

### 3. 🛡️ IT Security Audit & Risk Assessment (Mita School)

Overview:
This project presents a comprehensive security audit of Mita School, evaluating its cybersecurity posture, identifying vulnerabilities, and recommending risk mitigation strategies. The assessment was conducted in a structured and controlled manner for educational purposes.

Scope:
- Review of security policies and procedures
- Assessment of network, systems, and infrastructure security
- Evaluation of staff and student compliance with security practices

Methodology:
- Conducted risk identification and vulnerability analysis
- Evaluated existing administrative, technical, and physical controls
- Assessed compliance with cybersecurity best practices
- Developed actionable security recommendations

Key Findings:
- Weak password policies exposing systems to brute-force attacks
- Unsecured Wi-Fi network
- Lack of multi-factor authentication (MFA)
- Inadequate access control mechanisms
- Potential abuse of course access permissions

Recommendations:
- Implement CCTV surveillance systems
- Enforce secure Wi-Fi access controls
- Deploy access card authentication system
- Introduce multi-factor authentication (MFA)
- Restrict access strictly to enrolled courses

Result:
- Identified critical security gaps and provided practical mitigation strategies to improve institutional security posture

Key Insight:
Effective cybersecurity is not only technical but also requires strong policies, access control, and user accountability.

👉 [View Full Report (PDF)](./mita_school_security_audit.pdf)

### 4. Phishing Attack Simulation (MedusaPhisher)

This project demonstrates a controlled phishing attack simulation using MedusaPhisher to evaluate user susceptibility to social engineering attacks and credential harvesting techniques.

Tools & Environment:
- Tool: MedusaPhisher
- OS: Kali Linux
- Environment: Controlled / Localhost testing setup

Methodology:
- Configured a phishing template mimicking a legitimate login page  
- Generated a controlled phishing link within a safe test environment  
- Simulated user interaction with the phishing interface  
- Monitored credential capture process and analyzed behavior patterns  

Result:
- Successfully demonstrated how user credentials can be captured through phishing techniques in a controlled setup  

Key Insight:
Human factors remain one of the weakest links in cybersecurity—users are highly susceptible to well-crafted phishing attacks, especially without proper awareness training.

👉 [View Full Report (PDF)](./Phishing_Attack_Simulation_MedusaPhisher.pdf)


### 5. 🗄️ SQL Data Analysis & Database Operations Lab

This project demonstrates practical use of SQL for managing and analyzing relational databases, focusing on data manipulation, querying, and structural modifications to support efficient and secure data handling.

Tools & Environment:
- Tool: SQL (MySQL / SQLite)
- OS: Linux / Windows
- Database Type: Relational Database

Process:
- Created and structured database tables
- Performed data filtering using WHERE, AND, OR conditions
- Executed CRUD operations (INSERT, UPDATE, DELETE)
- Applied aggregate functions such as COUNT for data analysis
- Modified table structure using ALTER TABLE
- Queried and combined datasets where necessary

Result:
- Successfully demonstrated efficient data management and querying techniques
- Performed accurate data updates, deletions, and filtering operations

Key Insight:
Proper database management and query optimization are essential for maintaining data integrity, enabling efficient data retrieval, and supporting secure backend operations in cybersecurity and software systems.

👉 [View Full Report (PDF)](./SQL_Data_Analysis_&_Database_Operations_Lab.pdf)

### 5. 🖥️ Endpoint Security Monitoring (Sysmon)

Overview:
This project demonstrates the deployment and configuration of Sysmon to enhance endpoint visibility and detect suspicious system activity through detailed logging.

Tools & Environment:
- Tool: Sysmon
- OS: Windows
- Tools: PowerShell, Event Viewer
- Configuration: SwiftOnSecurity Sysmon config

Methodology:
- Installed and configured Sysmon on Windows system
- Applied a security-focused configuration file
- Monitored system events including process, network, and file activity
- Analyzed logs using Windows Event Viewer

Result:
- Successfully captured and analyzed system-level events such as process execution and network activity

Key Insight:
Endpoint monitoring tools like Sysmon provide deep visibility into system behavior and are essential for detecting threats such as reconnaissance, malware activity, and persistence mechanisms.

👉 [View Full Report (PDF)](./endpoint_security_monitoring_sysmon.pdf)

## Certifications

- SOC Level 1 Learning Path – TryHackMe (March 25, 2026)  
- Cyber Security 101 Learning Path – TryHackMe (February 13, 2026)  
- Advent of Cyber 2025 – TryHackMe  
  Demonstrated understanding of cybersecurity fundamentals, consistency, and continuous learning through hands-on challenges 

- Junior Cybersecurity Analyst Career Path – Cisco Networking Academy (December 31, 2025)   

---

## Learning & Labs

- Completed hands-on cybersecurity labs on TryHackMe (SOC Level 1, Cyber Security 101, Advent of Cyber)  
- Practiced penetration testing and exploitation labs on Hack The Box  
- Studied cybersecurity fundamentals through Cisco Networking Academy  
- Completed online cybersecurity courses on Coursera  
- Gained experience in network scanning, enumeration, and vulnerability assessment    

---

## Achievements

- Completed SOC Level 1 and Cyber Security 101 learning paths on TryHackMe, gaining practical experience in threat detection and analysis  
- Participated in Advent of Cyber 2025, demonstrating consistency and problem-solving across real-world cybersecurity scenarios  
- Built and executed hands-on labs in password hashing, network scanning, and vulnerability assessment  
- Successfully completed the Junior Cybersecurity Analyst Career Path through Cisco Networking Academy   

---

## Contact
Email:   soloub7@gmail.com
LinkedIn: www.linkedin.com/in/ubong-solomon-210358295
