# Detection Engineering Lab

A cybersecurity project demonstrating Sigma rule development, detection engineering, threat detection, and MITRE ATT&CK mapping.

---

## Overview

This project demonstrates how Security Detection Engineers create Sigma rules for identifying suspicious Windows security events.

The lab contains detections for:

- Failed Login Attempts
- Privilege Escalation
- Account Creation
- PowerShell Execution

---

# MITRE ATT&CK Mapping

| Event ID | Technique | Description |
|----------|-----------|-------------|
| 4625 | T1110 | Brute Force |
| 4672 | T1078 | Valid Accounts |
| 4720 | T1136 | Create Account |
| 4688 | T1059.001 | PowerShell |

---

## Detection Coverage

### Brute Force Detection

Event ID: 4625

Technique

T1110 – Brute Force

Severity

High

---

### Privilege Escalation

Event ID: 4672

Technique

T1078 – Valid Accounts

Severity

High

---

### Account Creation

Event ID: 4720

Technique

T1136 – Create Account

Severity

Medium

---

### PowerShell Execution

Event ID: 4688

Technique

T1059.001 – PowerShell

Severity

High

---

## ATT&CK Tactics Covered

- Credential Access
- Privilege Escalation
- Persistence
- Execution

---

## Recommendations

- Monitor failed logons
- Audit privileged accounts
- Review account creation
- Investigate PowerShell execution

---

## Screenshots

### Brute Force Rule

![Brute Force Rule](screenshots/brute_force_rule.png)

### Privilege Escalation Rule

![Privilege Escalation Rule](screenshots/privilege_escalation_rule.png)

### Account Creation Rule

![Account Creation Rule](screenshots/account_creation_rule.png)

### PowerShell Rule

![PowerShell Rule](screenshots/powershell_rule.png)

---

## Technologies Used

- Sigma
- MITRE ATT&CK
- Linux
- Bash
- Git
- GitHub
- Termux

---

## Reports

```text
Detection-Engineering-Lab
├── logs
│   └── security.log
├── reports
│   ├── detection_engineering_report.txt
│   └── mitre_mapping.md
├── screenshots
│   ├── brute_force_rule.png
│   ├── privilege_escalation_rule.png
│   ├── account_creation_rule.png
│   └── powershell_rule.png
├── sigma_rules
│   ├── account_creation_rule.yml
│   ├── brute_force_rule.yml
│   ├── powershell_rule.yml
│   └── privilege_escalation_rule.yml
└── README.md
```

---

## Learning Outcomes

- Detection Engineering
- Sigma Rule Development
- Threat Detection
- MITRE ATT&CK Mapping
- Security Monitoring
- SOC Operations
- Threat Hunting
- Incident Investigation

## Author

Thabo Sakonta

Microsoft Certified Security Operations Analyst (SC-200)

GitHub:
https://github.com/thabosakonta-wq

LinkedIn:
https://www.linkedin.com/in/thabo-sakonta-377a3748

---

## License

This project is provided for educational and portfolio purposes.
=======
Detection Investigation
