# Data Privacy and Compliance

## Overview
I conducted a compliance assessment focused on file permissions and access controls. The goal was to identify vulnerabilities that could expose sensitive data and implement remediations aligned with GDPR and HIPAA requirements.

## Key Findings
- Overly permissive file permissions
- Incorrect ownership configurations
- Insecure home directories
- World‑readable files

## Risks
- Unauthorized data access or modification
- Insider threats and privilege escalation
- Data leakage and compliance violations

## Remediations
- Restricted sensitive file permissions (e.g., `chmod 600`)
- Enforced least privilege access
- Secured ownership and directory configurations
- Improved monitoring and accountability

## Compliance Alignment
- GDPR Article 5(1)(f) – Integrity and confidentiality
- GDPR Article 32 – Technical safeguards
- HIPAA Security Rules – Access control and data protection
- CIS Linux Benchmarks – Secure permissions

## Lessons Learned
- Small misconfigurations can create major risks.
- Continuous monitoring and auditing are essential.
- Tools like **Lynis** help uncover hidden vulnerabilities.
- Compliance requires proactive, ongoing management.

## Conclusion
This project demonstrates how technical controls, auditing, and remediation improve data privacy posture, reduce breach risks, and strengthen compliance with industry regulations.
