---
description: Security baseline
applyTo: "**"
---
- Follow OWASP Top 10; validate all input; encode all output.
- No secrets in code or config; use environment variables or a vault.
- Every endpoint requires authentication and an explicit authorization rule.
- Never log PII or tokens.
