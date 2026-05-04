# Security Policy

## Supported Versions

The following versions of this project are currently supported with security updates:

| Version | Supported          |
| ------- | ------------------ |
| 1.x     | :white_check_mark: |
| < 1.0   | :x:                |

## Reporting a Vulnerability

We take security vulnerabilities seriously. If you discover a security issue in this project, please follow responsible disclosure practices.

**Please do NOT report security vulnerabilities through public GitHub issues.**

### How to Report

1. **Email**: Send a detailed report to the repository owner via GitHub's private vulnerability reporting feature, or contact the maintainer directly.
2. **GitHub Private Reporting**: Use [GitHub's private vulnerability reporting](../../security/advisories/new) to submit a report confidentially.

### What to Include

Please include as much of the following information as possible to help us understand and resolve the issue quickly:

- Type of vulnerability (e.g., XSS, CSRF, injection, etc.)
- Full path of the affected source file(s)
- Step-by-step instructions to reproduce the issue
- Proof-of-concept or exploit code (if available)
- Potential impact of the vulnerability

### Response Timeline

- **Acknowledgement**: Within 48 hours of receiving your report.
- **Initial Assessment**: Within 5 business days.
- **Resolution**: We aim to resolve critical vulnerabilities within 30 days.

You will be kept informed of the progress throughout the process.

## Security Best Practices for Contributors

When contributing to this project, please keep the following in mind:

- **Input Validation**: Always validate and sanitize user inputs to prevent XSS and injection attacks.
- **No Sensitive Data**: Do not commit credentials, API keys, tokens, or any sensitive data to the repository.
- **Dependencies**: Keep dependencies up to date and avoid introducing packages with known vulnerabilities.
- **Content Security**: Avoid using `eval()` or other unsafe JavaScript patterns.
- **HTTPS**: Ensure any external resources are loaded over HTTPS.

## Scope

This security policy applies to the source code hosted in this repository. Third-party libraries and dependencies are subject to their own security policies.

## Disclosure Policy

Once a vulnerability is resolved, we will:

1. Release a patched version as soon as possible.
2. Publish a security advisory describing the vulnerability, its impact, and the fix.
3. Credit the reporter (unless they prefer to remain anonymous).
