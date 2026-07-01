# MITRE ATT&CK Mapping

| Detection | Technique | Description |
|------------|------------|------------|
| Brute Force | T1110 | Brute Force |
| Privilege Escalation | T1078 | Valid Accounts |
| Account Creation | T1136 | Create Account |
| PowerShell Activity | T1059.001 | PowerShell |

MITRE ATT&CK Mapping

Detection Coverage

Detection| MITRE Technique| Description
Brute Force Detection| T1110| Brute Force
Privilege Escalation Detection| T1078| Valid Accounts
Account Creation Detection| T1136| Create Account
PowerShell Execution Detection| T1059.001| PowerShell

---

Detection Analysis

Brute Force Detection

Detection:
Multiple failed authentication attempts.

MITRE ATT&CK:

- T1110 – Brute Force

Severity:
High

---

## Technique Analysis

### T1110 – Brute Force

Detection:
Privileged account assignments detected.

Detects repeated authentication failures.

Severity: High

- T1078 – Valid Accounts

### T1078 – Valid Accounts

Detects privileged account assignments.

Severity: High

### T1136 – Create Account

Detects newly created accounts.

Severity: Medium

### T1059.001 – PowerShell

Detects PowerShell execution activity.

Severity: High

---

## Coverage Summary

ATT&CK Tactics Covered:

- Credential Access
- Execution
- Persistence
- Privilege Escalation

Detection:
New user account creation observed.

MITRE ATT&CK:

- T1136 – Create Account

Severity:
Medium

---

## Recommendations

- Monitor failed logons.
- Audit privilege assignments.
- Review account creation activity.
- Investigate PowerShell execution.

Detection:
PowerShell execution activity identified.

MITRE ATT&CK:

- T1059.001 – PowerShell

Severity:
High

---

Investigation Summary

Observed Activity

- Failed authentication attempts
- Privileged account activity
- New account creation
- PowerShell execution

Assessment

Potential attacker behavior requiring investigation and validation.

Recommended Actions

- Investigate authentication logs
- Review privileged account activity
- Validate new account creation
- Analyze PowerShell command execution
- Correlate findings with endpoint telemetry
