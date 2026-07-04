# Detection Engineering Lab

A cybersecurity project demonstrating Sigma rule development, Windows detection engineering, threat detection, and MITRE ATT&CK mapping.

---

# Overview

This project demonstrates how Security Detection Engineers create, document, and validate Sigma rules used to detect suspicious Windows Security Events.

The lab simulates a Detection Engineering workflow by identifying common attack techniques, developing Sigma detection rules, mapping detections to MITRE ATT&CK, and producing professional SOC documentation.

---

# Objectives

- Demonstrate Detection Engineering principles.
- Develop Sigma rules for Windows Security Events.
- Detect common attacker techniques.
- Map detections to the MITRE ATT&CK framework.
- Produce professional detection documentation.
- Demonstrate practical Detection Engineering skills expected of SOC Analysts.

---

# Features

## Failed Login Detection

- Detects Windows Event ID 4625
- Detects brute-force activity
- Sigma rule included

## Privileged Activity Detection

- Detects Windows Event ID 4672
- Identifies privileged account usage
- Detects possible privilege escalation

## Account Creation Detection

- Detects Windows Event ID 4720
- Detects unauthorized account creation
- Supports persistence detection

## PowerShell Detection

- Detects Windows Event ID 4688
- Detects PowerShell execution
- Supports execution technique detection

---

# MITRE ATT&CK Coverage

| Event ID | Technique | Description |
|----------|-----------|-------------|
|4625|T1110|Brute Force|
|4672|T1078|Valid Accounts|
|4720|T1136|Create Account|
|4688|T1059.001|PowerShell|

---

# Detection Coverage

| Detection | Event ID | Severity |
|----------|----------|----------|
|Failed Login Attempts|4625|High|
|Privilege Escalation|4672|High|
|Account Creation|4720|Medium|
|PowerShell Execution|4688|High|

---

# Technologies Used

- Sigma
- Bash
- Linux
- Termux
- Git
- GitHub
- Windows Security Event Logs
- MITRE ATT&CK

---

# Project Structure

```text
Detection-Engineering-Lab
├── logs
│   └── security.log
├── reports
│   ├── executive_summary.md
│   ├── detection_engineering_report.txt
│   └── mitre_mapping.md
├── screenshots
│   ├── brute_force_rule.png
│   ├── privilege_escalation_rule.png
│   ├── account_creation_rule.png
│   └── powershell_rule.png
├── sigma_rules
│   ├── brute_force_rule.yml
│   ├── privilege_escalation_rule.yml
│   ├── account_creation_rule.yml
│   └── powershell_rule.yml
└── README.md
```

---

# Reports

- reports/executive_summary.md
- reports/detection_engineering_report.txt
- reports/mitre_mapping.md

---

# Screenshots

## Brute Force Rule

![Brute Force Rule](screenshots/brute_force_rule.png)

## Privilege Escalation Rule

![Privilege Escalation Rule](screenshots/privilege_escalation_rule.png)

## Account Creation Rule

![Account Creation Rule](screenshots/account_creation_rule.png)

## PowerShell Rule

![PowerShell Rule](screenshots/powershell_rule.png)

---

# Learning Outcomes

- Detection Engineering
- Sigma Rule Development
- Threat Detection
- Security Monitoring
- MITRE ATT&CK Mapping
- Incident Investigation
- SOC Operations

---

# Future Enhancements

- Sigma Rule Testing
- Elastic SIEM Integration
- Splunk Integration
- Microsoft Sentinel Analytics Rules
- Microsoft Defender XDR
- Automated Detection Validation
- Sysmon Detection Rules

---

# Author

Thabo Sakonta

Microsoft Certified Security Operations Analyst (SC-200)

GitHub:
https://github.com/thabosakonta-wq

LinkedIn:
https://www.linkedin.com/in/thabo-sakonta-377a3748

---

# License

This project is provided for educational, research, and professional portfolio purposes.
