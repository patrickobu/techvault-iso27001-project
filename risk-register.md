# Risk Register

![Organisation](https://img.shields.io/badge/Organisation-TechVault%20Ltd-blue)
![Standard](https://img.shields.io/badge/Standard-ISO%2027001%3A2022-purple)
![Risks](https://img.shields.io/badge/Total%20Risks-25-orange)
![Critical](https://img.shields.io/badge/Critical-3-red)
![High](https://img.shields.io/badge/High-8-orange)

**Organisation:** TechVault Ltd
**Document:** ISO 27001:2022 Information Security Risk Register
**Version:** 1.0
**Date:** 2025

---

## Risk Assessment Methodology

Risks are assessed using a qualitative approach:

**Likelihood:** 1 (Rare) to 5 (Almost Certain)
**Impact:** 1 (Negligible) to 5 (Catastrophic)
**Risk Score:** Likelihood x Impact (1-25)

| Score | Level |
|-------|-------|
| 20-25 | CRITICAL |
| 12-19 | HIGH |
| 6-11 | MODERATE |
| 1-5 | LOW |

---

## Risk Register

| ID | Risk | Asset | Threat | Likelihood | Impact | Score | Level | Treatment | Owner |
|----|------|-------|--------|-----------|--------|-------|-------|-----------|-------|
| R-001 | Ransomware attack encrypts DocuVault data | Client documents | Cybercriminal | 4 | 5 | 20 | CRITICAL | Mitigate — EDR, immutable backups, IR plan | CISO |
| R-002 | Unauthorised access to client documents | Client documents | External attacker | 4 | 5 | 20 | CRITICAL | Mitigate — MFA, RBAC, encryption | CISO |
| R-003 | Developer credential compromise | Source code, production systems | Phishing, credential theft | 4 | 5 | 20 | CRITICAL | Mitigate — MFA for all devs, PAM solution | CTO |
| R-004 | Third-party supplier data breach | Client documents (via supplier) | Supplier incident | 3 | 5 | 15 | HIGH | Mitigate — supplier assessments, contractual requirements | Legal |
| R-005 | Insider threat — data exfiltration | Client documents | Disgruntled employee | 3 | 5 | 15 | HIGH | Mitigate — DLP, access monitoring, off-boarding | CISO |
| R-006 | SQL injection attack on DocuVault | Database | External attacker | 3 | 5 | 15 | HIGH | Mitigate — input validation, WAF, penetration testing | CTO |
| R-007 | Unpatched vulnerability exploited | Production servers | External attacker | 3 | 4 | 12 | HIGH | Mitigate — monthly patching, vulnerability scanning | CTO |
| R-008 | Social engineering attack on staff | All assets | External attacker | 4 | 3 | 12 | HIGH | Mitigate — security awareness training, phishing tests | CISO |
| R-009 | Data breach via unsecured API | Client data | External attacker | 3 | 4 | 12 | HIGH | Mitigate — API security testing, authentication | CTO |
| R-010 | Lost or stolen staff laptop | Client data | Physical theft | 3 | 4 | 12 | HIGH | Mitigate — full disk encryption, MDM, remote wipe | IT |
| R-011 | Accidental deletion of client data | Client documents | Human error | 3 | 4 | 12 | HIGH | Mitigate — versioning, backup, access controls | CTO |
| R-012 | DDoS attack causing service outage | DocuVault platform | Cybercriminal | 3 | 3 | 9 | MODERATE | Mitigate — DDoS protection, CDN, SLA monitoring | CTO |
| R-013 | Weak password leading to account takeover | User accounts | External attacker | 3 | 3 | 9 | MODERATE | Mitigate — MFA, password policy | IT |
| R-014 | Misconfigured cloud storage exposing data | Client documents | Misconfiguration | 2 | 4 | 8 | MODERATE | Mitigate — cloud security posture management | CTO |
| R-015 | Lack of staff security awareness | All assets | Internal/external | 4 | 2 | 8 | MODERATE | Mitigate — annual security training programme | HR |
| R-016 | Failure to comply with GDPR | Personal data | Regulatory | 2 | 4 | 8 | Mitigate | GDPR compliance programme | Legal |
| R-017 | System unavailability exceeding SLA | DocuVault platform | Technical failure | 2 | 4 | 8 | MODERATE | Mitigate — HA architecture, DR testing | CTO |
| R-018 | Insecure third-party code in dependencies | Production systems | Supply chain | 3 | 3 | 9 | MODERATE | Mitigate — SCA scanning in CI/CD pipeline | CTO |
| R-019 | Inadequate logging preventing forensics | All systems | Any incident | 3 | 3 | 9 | MODERATE | Mitigate — centralised logging, 12-month retention | CTO |
| R-020 | Physical intrusion at office | Servers, workstations | Physical attacker | 1 | 4 | 4 | LOW | Mitigate — access control, CCTV | Facilities |
| R-021 | Power failure causing system outage | Production systems | Environmental | 2 | 3 | 6 | MODERATE | Mitigate — UPS, cloud redundancy | CTO |
| R-022 | Key person dependency — CISO absence | Security programme | People risk | 2 | 3 | 6 | MODERATE | Mitigate — document procedures, deputy CISO | CEO |
| R-023 | Email phishing — financial fraud | Bank accounts | Financial crime | 3 | 2 | 6 | MODERATE | Mitigate — email security, finance controls | Finance |
| R-024 | USB device data exfiltration | Client data | Insider | 2 | 2 | 4 | LOW | Accept — USB ports disabled on critical systems | IT |
| R-025 | Natural disaster affecting office | Office, hardware | Environmental | 1 | 3 | 3 | LOW | Accept — cloud-hosted, office loss manageable | Facilities |

---

## Risk Treatment Summary

| Treatment | Count |
|-----------|-------|
| Mitigate | 23 |
| Accept | 2 |
| Transfer | 0 |
| Avoid | 0 |

All 3 CRITICAL risks have been assigned to the CISO or CTO with
a remediation target of 30 days. Progress is tracked in the
nonconformity tracker and reviewed monthly by the ISMS Committee.

---

*This document is part of a GRC portfolio project. All names,
data, and scenarios are fictional and used for learning and
career development purposes only.*

