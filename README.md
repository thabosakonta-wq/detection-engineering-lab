# Detection Engineering Lab

A cybersecurity project focused on detection engineering, Sigma rule development, threat detection, and MITRE ATT&CK mapping.

---

## Overview

This lab demonstrates how detection engineers create and document Sigma rules used to identify suspicious security events in enterprise environments.

The project includes detections for:

- Brute Force Attacks
- Privilege Escalation
- Account Creation
- PowerShell Activity

---

## Features

### Brute Force Detection

Detects multiple failed login attempts.

### Privilege Escalation Detection

Detects privileged account assignments.

### Account Creation Detection

Detects newly created user accounts.

### PowerShell Detection

Detects PowerShell execution activity.

## Screenshots

### Brute Force Detection Rule

![Brute Force Rule](screenshots/brute_force_rule.png)

### Privilege Escalation Detection Rule

![Privilege Escalation Rule](screenshots/privilege_escalation_rule.png)

---

## MITRE ATT&CK Coverage

| Technique | Description |
|------------|------------|
| T1110 | Brute Force |
| T1078 | Valid Accounts |
| T1136 | Create Account |
| T1059.001 | PowerShell |

---

## Technologies Used

- Sigma
- MITRE ATT&CK
- Linux
- Termux
- Git
- GitHub

---

## Project Structure

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

## Screenshots

![Failed Login Detection](screenshots/failed_login_analysis.png)

![Privileged Activity Detection](screenshots/privileged_activity_detection.png)

![Account Creation Detection](screenshots/account_creation_detection.png)

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
