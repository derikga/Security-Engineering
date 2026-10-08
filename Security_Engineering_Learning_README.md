# Security Engineering Learning Portfolio

A personal, hands-on repository for developing and demonstrating skills across enterprise security engineering. This repository documents what I learn, the labs I complete, and the tools and automations I build along the way.

## Goals

- Strengthen core knowledge of identity, endpoint, network, cloud, and data security.
- Develop a repeatable approach to investigating alerts, assessing risk, and validating controls.
- Practice security scripting, version control, and collaboration workflows.
- Build a record of practical work that demonstrates both technical understanding and sound security judgment.

## Learning areas

| Folder | Focus |
| --- | --- |
| `01-identity-access/` | IAM, SSO, MFA, privileged access, authentication protocols |
| `02-endpoint-detection/` | EDR, system telemetry, process analysis, detection engineering |
| `03-vulnerability-management/` | Scanning, prioritization, remediation, verification |
| `04-network-security/` | Network protocols, firewalls, VPN, TLS, segmentation |
| `05-device-management/` | MDM, device compliance, baseline hardening |
| `06-email-data-security/` | Phishing, email authentication, DLP, data protection |
| `07-cloud-saas-security/` | Cloud IAM, SaaS integrations, API permissions, AI tooling risk |
| `08-governance-risk-compliance/` | Risk assessments, control mapping, third-party security |
| `09-incident-response/` | Triage, evidence, containment, recovery, lessons learned |
| `10-security-automation/` | Python, PowerShell, shell scripting, CI/CD security |
| `11-git-github/` | Version control, branching, pull requests, GitHub Actions |

## How I work

1. Choose a topic and define the learning objectives.
2. Read documentation and complete a lab using a personal or isolated environment.
3. Record the approach, findings, limitations, and security considerations.
4. Create a feature branch, commit the work, and open a pull request for self-review.
5. Merge the reviewed changes and track what I can now explain or demonstrate.

## Typical project contents

- `README.md` — purpose, prerequisites, and key takeaways
- `notes/` — explanations and references
- `labs/` — reproducible exercise instructions using synthetic data
- `scripts/` — safe example automation with usage notes
- `diagrams/` — original architecture or workflow diagrams

Not every project will use every folder.

## Git workflow example

After creating and cloning a repository named `security-engineering-learning`:

```bash
git switch -c feature/iam-fundamentals
mkdir -p 01-identity-access
printf '# IAM Fundamentals\n' > 01-identity-access/README.md
git add 01-identity-access/README.md
git commit -m "docs: add IAM fundamentals notes"
git push -u origin feature/iam-fundamentals
```

Then open a pull request on GitHub, review the changes, and merge into `main`.

## Security and confidentiality

All examples are created for personal education using **synthetic or publicly available data**. Do not commit employer or customer information, credentials, tokens, private keys, production configurations, internal logs, proprietary source code, or sensitive incident evidence. Check files and Git history before publishing or changing repository visibility.

## Progress

Learning tasks and milestones may be tracked separately in Microsoft Planner. Completed labs and pull requests in this repository serve as supporting evidence of practice and understanding.

## References

- [Git documentation](https://git-scm.com/doc)
- [GitHub documentation](https://docs.github.com/)
- [MITRE ATT&CK](https://attack.mitre.org/)
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [Microsoft Learn](https://learn.microsoft.com/training/)
