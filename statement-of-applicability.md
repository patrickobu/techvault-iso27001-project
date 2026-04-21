# Statement of Applicability (SoA)

**Organisation:** TechVault Ltd
**Standard:** ISO/IEC 27001:2022 Annex A
**Version:** 1.0
**Date:** 2025

## Purpose

The Statement of Applicability documents which of the 93 ISO 27001
Annex A controls are applicable to TechVault's ISMS, whether each
is implemented, and the justification for any exclusions.

## Summary

| Theme | Total Controls | Applicable | Not Applicable |
|-------|---------------|-----------|---------------|
| Organisational | 37 | 35 | 2 |
| People | 8 | 8 | 0 |
| Physical | 14 | 10 | 4 |
| Technological | 34 | 32 | 2 |
| **Total** | **93** | **85** | **8** |

## Key Controls and Implementation Status

| Control | Name | Applicable | Status | Justification |
|---------|------|-----------|--------|--------------|
| A.5.1 | Policies for information security | Yes | Implemented | Top-level policy approved by CEO |
| A.5.2 | Information security roles | Yes | Implemented | CISO appointed |
| A.5.15 | Access control | Yes | Implemented | RBAC and MFA enforced |
| A.5.23 | Information security for cloud services | Yes | Partial | AWS security review in progress |
| A.6.1 | Screening | Yes | Implemented | Background checks for all staff |
| A.6.3 | Information security awareness | Yes | Partial | Training programme under development |
| A.7.1 | Physical security perimeters | Yes | Implemented | Office access controls in place |
| A.8.2 | Privileged access rights | Yes | Partial | PAM solution being procured |
| A.8.5 | Secure authentication | Yes | Gap | MFA not enforced for all developer accounts |
| A.8.8 | Management of technical vulnerabilities | Yes | Gap | No formal vulnerability scanning programme |

## Excluded Controls

| Control | Name | Justification for Exclusion |
|---------|------|-----------------------------|
| A.7.8 | Equipment siting and protection | TechVault is fully cloud-hosted. No on-premises servers. |
| A.7.9 | Security of assets off-premises | No physical media or equipment transported off-premises. |
| A.8.9 | Configuration management for physical media | Fully cloud-based — no physical media used. |
| A.5.22 | Monitoring supplier service delivery (manufacturing) | Not applicable to SaaS operations. |
