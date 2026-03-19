# Security Policy

## Overview

TOTPBOX takes the security of our platform and users seriously. We appreciate the work of security researchers and the responsible disclosure community. If you believe you have found a security vulnerability in any TOTPBOX product or service, please notify us promptly.

---

## Supported Versions

We actively support and provide security patches for the following versions:

| Version | Supported |
|---|---|
| Latest stable | YES |
| Previous stable | YES (critical only) |
| Older versions | NO |

---

## Reporting a Vulnerability

> **Please do NOT open a public GitHub issue to report a security vulnerability.** Public disclosure before a fix is available puts all users at risk.

### How to Report

**Email:** Send your report to [totpbox@gmail.com](mailto:totpbox@gmail.com)  
**Subject line:** `[SECURITY] <brief description>`

Please include as much of the following information as possible:

- **Description** of the vulnerability
- **Type** of vulnerability (e.g., XSS, CSRF, injection, authentication bypass, etc.)
- **Affected product/component** (Web app, API, etc.)
- **Steps to reproduce** — detailed, reproducible steps
- **Impact** — what could an attacker achieve?
- **Proof of concept** — screenshots, videos, or code snippets (optional but very helpful)
- **Suggested fix** (optional)

---

## What to Expect

| Timeline | Action |
|---|---|
| Within 48 hours | Acknowledgement of your report |
| Within 7 days | Initial assessment and severity rating |
| Within 30 days | Resolution target for critical/high severity issues |
| Upon fix | Coordinated disclosure — we'll notify you before publishing |

---

## Scope

### In Scope

- **TOTPBOX Web App** — [totpbox.com](https://totpbox.com)
- **TOTPBOX API** (when available) — authentication, authorization, data exposure
- **TOTPBOX SDKs** (when available) — security logic, token handling

### Out of Scope

- Denial of service (DoS/DDoS) attacks
- Social engineering or phishing attacks
- Physical security issues
- Vulnerabilities in third-party services or dependencies (please report these to the respective maintainers)
- Issues already known or previously reported
- Theoretical vulnerabilities without proof of exploitability

---

## Recognition

We genuinely appreciate the security research community's efforts. Researchers who responsibly disclose valid vulnerabilities will be acknowledged in our security advisories (with your permission).

---

## Contact

For security-related inquiries: [totpbox@gmail.com](mailto:totpbox@gmail.com)  
For general questions, please use [GitHub Issues](https://github.com/TOTPBOX/totpbox/issues).
