![Cybersecurity](https://img.shields.io/badge/Field-Cybersecurity-blue) ![Focus](https://img.shields.io/badge/Focus-SOC%20Analyst-green) ![Level](https://img.shields.io/badge/Level-Entry--Level-orange)

# 👨‍💻 Cybersecurity Portfolio

## About Me
Aspiring Cybersecurity Analyst with hands-on experience in threat detection, network security, and security monitoring. Skilled in using tools such as Sysmon, John the Ripper, and Aircrack-ng to identify vulnerabilities and analyze system activity. Experienced in conducting security assessments, simulating real-world attacks, and analyzing logs to detect suspicious behavior. Passionate about blue team operations, endpoint monitoring, and improving organizational security posture.
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
## 🎯 Career Focus
Aspiring SOC Analyst with a focus on threat detection, endpoint monitoring, and security analysis.

---

## 📊 Project Summary

Below is a summary of my hands-on cybersecurity projects, highlighting domain, tools used, and skills demonstrated.

| # | Project | Focus Area | Skills Demonstrated |
|---|--------|-----------|--------------------|
| 1 | Password Hash Analysis & Recovery (John the Ripper) | System Security | Password auditing, hash analysis, dictionary attacks |
| 2 | Wireless Security Assessment (Aircrack-ng) | Network Security | Wi-Fi security testing, packet capture, vulnerability analysis |
| 3 | IT Security Audit & Risk Assessment (Mita School) | GRC | Risk assessment, policy evaluation, security recommendations |
| 4 | Phishing Attack Simulation (MedusaPhisher) | Social Engineering | Credential harvesting, attack simulation, user awareness testing |
| 5 | SQL Data Analysis & Database Operations Lab | Data Security | Database management, querying, CRUD operations, data analysis |
| 6 | Endpoint Security Monitoring (Sysmon) | Blue Team / SOC | Event log monitoring, process & network activity analysis, threat detection |
| 7 | SIEM Log Analysis & Threat Detection (Splunk + Sysmon) | SOC / Threat Detection | Log ingestion, security monitoring, detection queries, simulated attacks |
| 8 | Suricata IDS Deployment & Packet Analysis Lab | Network Security / IDS | Intrusion detection, packet analysis, traffic inspection, threat correlation |

---

## Projects

### 1. Password Hash Analysis & Recovery (John the Ripper)

Overview:
This project demonstrates a controlled password auditing exercise using a dictionary attack to identify weak credentials.

Tools & Environment:
- Tool: John the Ripper
- OS: Linux
- Wordlist: rockyou.txt

Methodology:
- Prepared password hash file for analysis
- Executed cracking using John the Ripper
- Matched hashes against a wordlist

Result:
- Investigated and recovered a weak password from the hash

Key Insight:
Weak passwords are highly vulnerable to dictionary-based attacks, emphasizing the need for strong password policies.

👉 [View Full Report](./password_hash_analysis_john_the_ripper.pdf)

---

### 2. 📡 Wireless Security Assessment (Aircrack-ng)

Overview:
This project demonstrates a controlled wireless network security assessment using Aircrack-ng to evaluate Wi-Fi security and identify vulnerabilities in weak encryption configurations.

Tools & Environment:
- Tool: Aircrack-ng suite
- OS: Linux
- Mode: Monitor mode enabled wireless adapter

Methodology:
- Enabled monitor mode on wireless interface
- Captured network packets and WPA/WEP handshake
- Performed password cracking using captured handshake
- Analyzed network security strength

Result:
- Simulated and validated how weak Wi-Fi passwords can be compromised

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

Overview:
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
- Simulated and validated how user credentials can be captured through phishing techniques in a controlled setup  

Key Insight:
Human factors remain one of the weakest links in cybersecurity—users are highly susceptible to well-crafted phishing attacks, especially without proper awareness training.

👉 [View Full Report (PDF)](./Phishing_Attack_Simulation_MedusaPhisher.pdf)


### 5. 🗄️ SQL Data Analysis & Database Operations Lab

Overview:
This project demonstrates practical use of SQL for managing and analyzing relational databases, focusing on data manipulation, querying, and structural modifications to support efficient and secure data handling.

Tools & Environment:
- Tool: SQL (MySQL / SQLite)
- OS: Linux / Windows
- Database Type: Relational Database

Methodology:
- Created and structured database tables
- Performed data filtering using WHERE, AND, OR conditions
- Executed CRUD operations (INSERT, UPDATE, DELETE)
- Applied aggregate functions such as COUNT for data analysis
- Modified table structure using ALTER TABLE
- Queried and combined datasets where necessary

Result:
- Identified and analyzed efficient data management and querying techniques
- Performed accurate data updates, deletions, and filtering operations

Key Insight:
Proper database management and query optimization are essential for maintaining data integrity, enabling efficient data retrieval, and supporting secure backend operations in cybersecurity and software systems.

👉 [View Full Report (PDF)](./SQL_Data_Analysis_&_Database_Operations_Lab.pdf)

### 6. 🖥️ Endpoint Security Monitoring (Sysmon)

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
- Analyzed multiple system events including process creation, network connections, and file activity logs.

Key Insight:
Endpoint monitoring tools like Sysmon provide deep visibility into system behavior and are essential for detecting threats such as reconnaissance, malware activity, and persistence mechanisms.

👉 [View Full Report (PDF)](./endpoint_security_monitoring_sysmon.pdf)

### 7. 📊 SIEM Log Analysis & Threat Detection (Splunk + Sysmon)

Overview:
This project demonstrates the implementation of a basic SIEM environment using Splunk and Sysmon to collect, analyze, and detect suspicious system activity.

Tools & Environment:
- SIEM: Splunk
- Endpoint Monitoring: Sysmon
- OS: Windows
- Log Source: Windows Event Logs

Methodology:
- Configured Sysmon for detailed endpoint logging
- Integrated Sysmon logs into Splunk using Universal Forwarder
- Simulated system activity and basic attack behaviors
- Created search queries to detect suspicious processes and commands

Detection Use Cases:
- Process execution monitoring
- Suspicious PowerShell activity
- Network connection analysis
- Basic reconnaissance detection

Key Queries:
- Detect PowerShell execution:
  index=* EventCode=1 CommandLine="*powershell*"

- Detect execution policy bypass:
  index=* CommandLine="*ExecutionPolicy Bypass*"

- Detect network connections:
  index=* EventCode=3

Result:
- Successfully ingested and analyzed system logs in Splunk
- Analyzed multiple Sysmon event logs including process creation, network connections, and command execution patterns to detect simulated attack behaviors.

Key Insight:
SIEM tools provide centralized visibility into system activity and enable security analysts to detect and respond to potential threats in real time.

👉 [View Full Report (PDF)](./Cybersecurity_Lab_Detecting_Attacks_with_Splunk_SIEM_and_Sysmon_Logs.pdf)


### 8. 🔐 Suricata IDS Deployment & Packet Analysis Lab

Overview:
This project demonstrates the deployment and practical use of a network-based Intrusion Detection System (IDS) using Suricata. It focuses on detecting and analyzing both network-layer and application-layer attacks through real-time monitoring and packet inspection.

The lab simulates real-world SOC scenarios by generating attack traffic (Nmap reconnaissance and SQL injection) and correlating IDS alerts with packet-level evidence using Wireshark.

Tools & Environment:
- IDS Engine: Suricata  
- Packet Analysis: Wireshark  
- Attacker Machine: Kali Linux  
- Target System: Metasploitable2 (DVWA)  
- Network Setup: Virtual Lab (NAT / Host-Only)  
- Protocols Analyzed: TCP, HTTP  

Methodology:
- Configured Suricata IDS with custom network settings (`HOME_NET`)  
- Deployed IDS in live monitoring mode on network interface  
- Simulated reconnaissance attack using Nmap SYN scan  
- Performed SQL Injection attack on DVWA web application  
- Captured live traffic using Wireshark  
- Applied filters to isolate attack traffic  
- Correlated Suricata alerts with packet-level data (IP, timestamps, payloads)  
- Analyzed attack patterns and IDS detection behavior  

Results:
- Detected Nmap SYN scan using Suricata ET SCAN rules  
- Identified SQL injection attempts in HTTP traffic  
- Captured SYN packets indicating port scanning behavior  
- Extracted SQL injection payloads from HTTP requests  
- Correlated IDS alerts with actual packet-level evidence  

Key Insights:
- Suricata effectively detects both network and application-layer attacks, demonstrating its capability as a reliable IDS solution  
- SYN scan behavior reveals reconnaissance activity through repeated connection attempts across multiple ports  
- Packet analysis using Wireshark validates IDS alerts and enhances investigation accuracy at the traffic level  
- SQL injection vulnerabilities highlight the risks of improper input validation in web applications  
- Correlating IDS alerts with packet data is essential for accurate threat detection and analysis in SOC environments  
- The project demonstrates practical skills in IDS deployment, network traffic analysis (TCP/IP, HTTP), and alert investigation  
- Packet-level forensic analysis provides deeper visibility into attack behavior and network interactions  
- Simulating real-world attack scenarios supports understanding of SOC workflows and incident response processes  
- Effective network security monitoring requires combining IDS detection with deep packet analysis to identify, validate, and interpret malicious activity
- 
👉 [View Full Report (PDF)](./Intrusion_Detection_System_Suricata_Report.pdf)


### 9. 🔐 Web Application Security Assessment & Vulnerability Testing (Byte Connect API)

Overview:
This project focuses on a practical cybersecurity assessment of the Byte Connect web application backend. The objective was to evaluate the API’s security posture, identify vulnerabilities, and simulate real-world attack scenarios in a controlled environment.

Scope:
- Testing of backend API endpoints
- Evaluation of authentication mechanisms
- Assessment of input validation and error handling
- Analysis of API response behavior under attack conditions

Methodology:
- Conducted black-box penetration testing using Postman
- Performed endpoint discovery and request analysis
- Simulated common attacks:
  - SQL Injection
  - Invalid input and malformed requests
  - Authentication bypass attempts
- Evaluated system responses and security controls

Key Findings:
- API properly validates user input and prevents empty submissions
- No SQL injection vulnerability detected during testing
- Secure error messages prevent information disclosure (e.g., generic “Invalid credentials”)
- Missing or misconfigured endpoint (`/api/auth/register`)
- No visible rate limiting (potential brute-force attack risk)
- Authorization mechanisms not fully exposed/tested

Recommendations:

- Implement JWT-based authentication for secure access control
- Introduce rate limiting to mitigate brute-force attacks
- Enforce strict input validation using validation libraries
- Complete and properly configure all API endpoints
- Implement role-based access control (RBAC)
- Add logging and monitoring for suspicious activities

Result:

* Successfully identified security strengths and potential vulnerabilities
* Provided actionable recommendations to improve API security and resilience

Key Insight:
Securing APIs requires a combination of **input validation, proper authentication, and proactive vulnerability testing** to prevent exploitation.

👉 [View Full Report (PDF)](./web_app_security_assessment.pdf)

---

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

## 📫 Contact
- Email: soloub7@gmail.com  
- LinkedIn: https://www.linkedin.com/in/ubong-solomon-210358295
