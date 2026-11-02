# Security Policy — Armpix Security Suite

We appreciate responsible security research and will work with reporters to investigate and address valid vulnerabilities.

## Report a Vulnerability

Please use one of these private channels:

- **GitHub:** [Create a private security advisory](https://github.com/ART449/Armpix-segurity-suite/security/advisories/new).
- **Email:** [arturo@iartlabs.com](mailto:arturo@iartlabs.com).

Do not report security vulnerabilities in public issues, discussions, or pull requests. There is no published PGP key; please use the private advisory channel if you need encrypted communication.

## Include in Your Report

If available, include:

- The affected component and version or commit.
- A concise description of the vulnerability and its potential impact.
- Reproduction steps or a minimal proof of concept.
- Any relevant configuration or logs, with secrets and personal data removed.

Please do not include passwords, tokens, or real users' personal data in a report.

## Researcher Guidelines

- Test only systems you own or are explicitly authorized to assess, preferably in a local or controlled environment.
- Do not access, modify, or disclose other people's data; do not disrupt services or conduct denial-of-service testing.
- Stop testing and report the issue promptly if you encounter sensitive data or unexpected access.
- Give us a reasonable opportunity to investigate and address the issue before public disclosure. We will coordinate disclosure timing with you.

## Scope

This policy covers Armpix components maintained and distributed by this project, including the REST API, web dashboard, CLI, mobile/PWA clients, Docker deployment configuration, and URL scanning and threat-detection engine, where present.

A third-party dependency is in scope when its vulnerability makes a supported Armpix version vulnerable. Issues confined to a third-party service or product not operated or maintained by this project should be reported to its provider.

Social engineering, physical security, and denial-of-service findings are out of scope. Do not test third-party systems without their authorization.

## Response

We aim to:

- Acknowledge a report within **2 business days**.
- Provide an initial assessment within **5 business days**.
- Keep the reporter informed if investigation or remediation takes longer.

Remediation timing depends on the issue's severity and complexity. Valid reports may be acknowledged in a security advisory or other project materials only with the reporter's permission.

## Supported Versions

No versioned releases or tags are currently published. Until releases are published, the latest code on the `main` branch is the only supported version. This section will be updated as supported releases are established.
