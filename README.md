# Deandre Wilson

Information security investigator moving into cloud security engineering on AWS. My background is in security investigations and operations, so I build from the analyst's side: how an incident is detected, what evidence matters, and how a response can be controlled and verified.

I document my work as I build. Each project lives in its own repository with its design decisions, validation evidence, and lessons learned.

---

## Featured Projects

| Project | What it demonstrates | Status |
|---|---|---|
| [`aws-labs`](https://github.com/NestHunter/aws-labs) | Hands-on AWS builds and troubleshooting across VPC networking, NAT, Lambda in a VPC, API Gateway, SQS, DynamoDB, EBS, and ALB. | 8 labs documented |
| [`aws-iam-security-policies`](https://github.com/NestHunter/aws-iam-security-policies) | IAM access control assessment (identity and resource policies, ABAC, permissions boundaries) and a least-privilege policy library (SCPs, KMS, cross-account roles, VPC Flow Logs). | Active |

## Building Next

- **DAST findings triage:** A Python CLI that deduplicates scanner findings across scans, applies severity-based remediation SLAs, and produces a prioritized report.
- **CloudTrail detection rules:** Sigma rules for high-signal AWS events, mapped to MITRE ATT&CK and tested against sample events.
- **Secure S3 Terraform module:** Encryption, public access blocking, versioning, and access logging by default, scanned with Checkov in CI.
- **KEV prioritizer:** Matches findings against the CISA Known Exploited Vulnerabilities catalog to decide what gets fixed first.

---

## Certifications

**Cloud**
- AWS Certified Solutions Architect - Associate
- HashiCorp Certified: Terraform Associate
- AWS Certified AI Practitioner
- AWS Certified Cloud Practitioner - Foundational

**Security**
- CompTIA SecurityX (formerly CASP+)
- CompTIA CySA+
- CompTIA Security+
- ISC2 Certified in Cybersecurity (CC)

## Currently

- Studying for the **AWS Certified Security - Specialty (SCS-C03)**
- Building small, focused security tools, starting with DAST findings triage

## Focus Areas

- Application security and vulnerability management
- Threat detection and incident response in AWS
- IAM, least privilege, and preventive guardrails
- Infrastructure as Code with Terraform
- Python for security automation

## Approach

- Build around real security workflows rather than isolated demos
- Validate every step and document failures alongside successes
- Separate what was tested from what is planned
- Keep public evidence sanitized

## Connect

- [LinkedIn](https://www.linkedin.com/in/deandre-wilson-939217141)
- [CyberNest](https://cybernesthub.com/)
