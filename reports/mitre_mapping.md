# MITRE ATT&CK Mapping

| Detection | Technique | Description |
|------------|------------|------------|
| Brute Force | T1110 | Brute Force |
| Privilege Escalation | T1078 | Valid Accounts |
| Account Creation | T1136 | Create Account |
| PowerShell Activity | T1059.001 | PowerShell |

---

## Technique Analysis

### T1110 – Brute Force

Detects repeated authentication failures.

Severity: High

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

---

## Recommendations

- Monitor failed logons.
- Audit privilege assignments.
- Review account creation activity.
- Investigate PowerShell execution.
