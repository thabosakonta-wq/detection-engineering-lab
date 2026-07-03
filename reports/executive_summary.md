# Executive Summary

## Detection Engineering Lab

### Objective

This project demonstrates the development of Sigma detection rules for identifying suspicious Windows Security Events commonly encountered by Security Operations Center (SOC) analysts.

The lab focuses on converting attacker behaviors into reusable detection logic while aligning detections with the MITRE ATT&CK framework.

---

## Detection Coverage

The following security events were covered:

| Detection | Event ID | Severity |
|-----------|----------|----------|
| Failed Login Attempts | 4625 | High |
| Privilege Escalation | 4672 | High |
| Account Creation | 4720 | Medium |
| PowerShell Execution | 4688 | High |

---

## MITRE ATT&CK Coverage

| Technique | ID |
|-----------|----|
| Brute Force | T1110 |
| Valid Accounts | T1078 |
| Create Account | T1136 |
| PowerShell | T1059.001 |

---

## Detection Engineering Summary

Sigma detection rules were developed for each Windows Security Event.

These detections provide standardized, SIEM-independent detection logic capable of identifying attacker techniques across multiple platforms.

---

## Recommendations

- Continuously tune Sigma rules to reduce false positives.
- Validate detections using production telemetry.
- Integrate Sigma rules into SIEM platforms.
- Maintain ATT&CK mappings for detection coverage.

---

**Status:** Detection Rules Validated

**Outcome:** Sigma rules successfully detect common Windows attack techniques while supporting SOC investigations.
