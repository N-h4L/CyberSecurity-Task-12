# Cyber Security Internship – Task 12

## 📌 Task Title
Log Monitoring & Analysis

## 🎯 Objective
The objective of this task was to understand system log monitoring and analysis using Kali Linux. The task focused on identifying authentication events, analyzing system activity, detecting anomalies, and understanding the importance of logs in cyber security and incident detection.

## 🛠 Tools Used
- Kali Linux
- Linux System Logs (/var/log)
- Terminal Commands (last, lastb, less, ls)

## 🧪 Practical Implementation

### 1. Log Directory Exploration
The /var/log directory was explored to identify available log files. Important log files found include:
- boot.log → System startup logs
- dpkg.log → Software installation and configuration logs
- btmp → Failed login attempts
- wtmp → Successful login sessions
- apache2, postgresql → Application logs

These logs store critical system and security information.

### 2. System Startup Log Analysis
The boot.log file was analyzed to review system startup events. The logs showed successful initialization of system services such as networking, firewall, and system timers, confirming normal system startup.

### 3. Package Management Log Analysis
The dpkg.log file was analyzed to monitor software installation and configuration activities. The logs showed installation and configuration of system packages such as OpenJDK and Neo4j. This confirms that Linux records all software changes.

### 4. Authentication Log Analysis
The wtmp log file was analyzed using the `last` command. The logs showed successful login sessions for the authorized user "nihal". Authentication logs help detect unauthorized access attempts.

### 5. Failed Login Monitoring
Failed login attempts are stored in the btmp file. Monitoring failed logins helps detect brute-force attacks and unauthorized access attempts.

## 🔍 Key Findings
- System logs were successfully monitored and analyzed
- Login activity was normal and authorized
- System startup processes were successfully completed
- Software installation events were properly recorded
- No suspicious or malicious activity was detected

## 🛡 Importance of Log Monitoring
Log monitoring is essential for:
- Detecting unauthorized access
- Monitoring system activity
- Identifying security incidents
- Supporting forensic investigations
- Improving overall system security

## 📚 SIEM Overview
Security Information and Event Management (SIEM) tools collect and analyze logs to detect threats. Examples include:
- Splunk
- ELK Stack
- IBM QRadar

These tools help automate security monitoring and incident detection.

## ⚠️ Disclaimer
This task was performed in a controlled lab environment for educational purposes only. No real systems were harmed or attacked.

## 👤 Author
Mohammed Nihal  
Cyber Security Intern
