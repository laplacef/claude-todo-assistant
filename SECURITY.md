# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| latest  | Yes       |

Only the latest release receives security patches.

## Reporting a Vulnerability

**Do not open a public GitHub issue for security vulnerabilities.**

To report a vulnerability, use [GitHub's private vulnerability reporting](https://github.com/laplacef/claude-todo-assistant/security/advisories/new). You can expect an initial response within 72 hours.

Please include:
- A description of the vulnerability
- Steps to reproduce the issue
- Potential impact assessment

## Scope

The following are considered security issues:
- Command definitions that read or exfiltrate vault contents beyond their stated purpose
- Injection through note content that causes unintended file writes or deletions
- Credential or personal data exposure through committed examples

## Out of Scope

The following are **not** security issues:
- Vulnerabilities in Obsidian or in the assistant tooling itself
- Task data loss from ordinary user error
- Accuracy of generated summaries
