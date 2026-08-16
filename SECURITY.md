# Security Policy

RuleBeat is a Reader-only tool: it never holds Azure write credentials and
never blocks deployments. We still take vulnerability reports seriously,
including in the scanning, auth, and RBAC paths.

## Reporting a vulnerability

Email **security@rulebeat.com**. Please include:

- A description of the issue and its impact
- Steps to reproduce, or a proof of concept
- The affected version or commit

Do not open a public GitHub issue for a security report.

## What to expect

We aim to acknowledge reports within 5 business days. We'll keep you updated
as we investigate and fix confirmed issues, and we'll credit reporters who
want credit once a fix ships.

## Scope

This policy covers the RuleBeat codebase and its official Docker images.
Third-party integrations you configure yourself (Teams, Slack, SMTP, your own
Azure tenant) are outside our scope.
