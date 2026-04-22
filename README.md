# TechVault Ltd — ISO 27001:2022 Project

![Framework](https://img.shields.io/badge/Standard-ISO%2027001%3A2022-purple)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![Organisation](https://img.shields.io/badge/Organisation-TechVault%20Ltd-blue)
![Sector](https://img.shields.io/badge/Sector-Cloud%20Software-teal)

---

## About This Project

This project demonstrates a full implementation of **ISO/IEC 27001:2022**
for TechVault Ltd — a fictional cloud software company offering a
document management platform to legal and financial services clients.

The project produces an Information Security Management System (ISMS)
including a risk register, Statement of Applicability (SoA), internal
audit report, and management review.

> All names, data, and scenarios are fictional. Created for portfolio
> and learning purposes only.

---

## About TechVault Ltd

TechVault Ltd is a fictional UK-based cloud software company with
80 employees. It develops and operates DocuVault — a cloud-based
document management platform used by 150 law firms and financial
services companies. Clients store highly confidential legal and
financial documents on the platform.

| Field | Value |
|-------|-------|
| Organisation | TechVault Ltd |
| Sector | Cloud software (SaaS) |
| Location | London, UK (fictional) |
| Employees | 80 |
| Clients | 150 law firms and financial companies |
| Product | DocuVault — cloud document management |
| Data | Confidential legal and financial documents |
| Driver for ISO 27001 | Client contractual requirement |

---

## What is ISO 27001?

ISO/IEC 27001:2022 is the international standard for Information
Security Management Systems (ISMS). It provides a framework for
establishing, implementing, maintaining, and continuously improving
information security.

Unlike NIST frameworks which are US-government focused, ISO 27001
is internationally recognised and is required by many enterprise
clients as a condition of doing business.

Key components:

| Component | Description |
|-----------|-------------|
| ISMS | The overall management system for information security |
| Risk assessment | Identifying and evaluating information security risks |
| Annex A controls | 93 security controls across 4 themes |
| Statement of Applicability | Documents which controls apply and why |
| Internal audit | Independent review of ISMS effectiveness |
| Management review | Senior leadership review of ISMS performance |

---

## Project Documents

| File | Description |
|------|-------------|
| `README.md` | This file — project overview |
| `isms-scope.md` | ISMS scope definition and boundaries |
| `information-security-policy.md` | TechVault's top-level security policy |
| `risk-assessment.md` | Risk assessment methodology and results |
| `risk-register.md` | 25 identified risks with ratings and treatments |
| `statement-of-applicability.md` | All 93 Annex A controls assessed |
| `internal-audit-report.md` | Internal ISMS audit findings |
| `management-review.md` | Management review of ISMS performance |
| `nonconformity-tracker.md` | Nonconformities and corrective actions |

---

## ISO 27001 Annex A Themes

ISO 27001:2022 organises its 93 controls into four themes:

| Theme | Controls | Focus |
|-------|---------|-------|
| Organisational controls | 37 | Policies, roles, supplier management, incident response |
| People controls | 8 | Screening, training, disciplinary process |
| Physical controls | 14 | Secure areas, equipment security, clear desk |
| Technological controls | 34 | Access control, encryption, logging, vulnerability management |

---

## Risk Assessment Summary

TechVault's risk assessment identified 25 information security risks.

| Risk Level | Count | Treatment |
|-----------|-------|-----------|
| CRITICAL | 3 | Immediate treatment required |
| HIGH | 8 | Treatment within 30 days |
| MODERATE | 10 | Treatment within 90 days |
| LOW | 4 | Accept or treat opportunistically |

### Top 5 Risks

| Risk | Level | Treatment |
|------|-------|-----------|
| Ransomware attack on DocuVault platform | CRITICAL | Mitigate — enhanced backup, EDR, incident response |
| Unauthorised access to client documents | CRITICAL | Mitigate — MFA, RBAC, access review |
| Data breach via compromised developer credentials | CRITICAL | Mitigate — privileged access management, MFA |
| Third-party supplier data exposure | HIGH | Mitigate — supplier security assessments |
| Insider threat from disgruntled employee | HIGH | Mitigate — access monitoring, off-boarding procedure |

---

## Statement of Applicability Summary

All 93 ISO 27001:2022 Annex A controls were assessed for applicability
to TechVault's ISMS scope.

| Category | Applicable | Not Applicable | Reason for Exclusion |
|----------|-----------|---------------|---------------------|
| Organisational (37) | 35 | 2 | Controls specific to physical manufacturing (not applicable to SaaS) |
| People (8) | 8 | 0 | All applicable |
| Physical (14) | 10 | 4 | Physical media controls not applicable (fully cloud-based) |
| Technological (34) | 32 | 2 | Legacy system controls not applicable |
| **Total (93)** | **85** | **8** | |

---

## Internal Audit Summary

An internal ISMS audit was conducted covering all applicable controls.

| Result | Count |
|--------|-------|
| Conformant | 71 controls |
| Minor nonconformity | 10 controls |
| Major nonconformity | 4 controls |
| Observation | 8 controls |

### Major Nonconformities

| Ref | Control | Finding |
|-----|---------|---------|
| NC-001 | A.8.8 — Vulnerability management | No formal vulnerability scanning programme in place |
| NC-002 | A.6.8 — Information security events | No formal incident reporting process documented |
| NC-003 | A.5.30 — ICT readiness for business continuity | Business continuity plan not tested in 18 months |
| NC-004 | A.8.5 — Secure authentication | MFA not enforced for all developer accounts |

All major nonconformities have been entered into the corrective
action tracker with owners and target dates.

---

## Management Review Summary

TechVault's management review concluded that:
- The ISMS is generally well-structured but requires investment in
  technical controls, particularly vulnerability management and MFA
- The four major nonconformities must be resolved within 60 days
- Budget has been approved for a vulnerability scanning tool and
  privileged access management solution
- The next internal audit is scheduled in six months

---

## Document Version History

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | 2025 | Portfolio Author | Initial ISO 27001 ISMS documentation completed |

---

*This document is part of a GRC portfolio project. All names,
data, and scenarios are fictional and used for learning and
career development purposes only.*

