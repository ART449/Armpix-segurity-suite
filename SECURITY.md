# Security Policy — Armpix Security Suite

## Reporting a Vulnerability

We take security vulnerabilities seriously. If you discover a security issue in Armpix, please report it responsibly.

## How to Report

1. **Email:** arturo@iartlabs.com
2. **PGP Key:** Not yet published. Contact via email first.
3. **GitHub:** Open a private security advisory at https://github.com/ART449/Armpix-segurity-suite/security/advisories/new

**Do NOT** open a public issue for security vulnerabilities.

## What to Include

- Type of vulnerability (XSS, CSRF, injection, auth bypass, etc.)
- Affected component/endpoint
- Steps to reproduce
- Potential impact
- Suggested fix (if any)

## Response Timeline

- **Acknowledgment:** Within 48 hours
- **Initial Assessment:** Within 5 business days
- **Fix Released:** As soon as possible, depending on severity

## Scope

This policy covers:
- Armpix REST API (FastAPI backend)
- Armpix Web Dashboard
- Armpix CLI tool
- Armpix Mobile (PWA + React Native)
- Docker deployment configuration
- URL scanning and threat detection engine

## Out of Scope

- Vulnerabilities in third-party dependencies (report to upstream)
- Social engineering or phishing attacks
- DoS/DDoS attacks
- Physical security issues

## Recognition

We maintain a hall of fame for responsible disclosures. Researchers who report valid vulnerabilities will be acknowledged (with permission) in the project's security advisory page.

## Compliance

Armpix follows:
- OWASP Top 10 mitigation guidelines
- CWE/SANS Top 25 Most Dangerous Software Errors
- GDPR-compliant data handling (no user data logged without consent)

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest (main) | Yes |
| < 1.0.0 | No |

---

Secured by Colmena — CETACEA Audit Approved
