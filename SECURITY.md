# Security Policy

## Scope

This repository currently contains documentation only. Security review still applies because the handbook will define future platform architecture, data boundaries, authentication models, authorization rules, AI runtime behavior, and operational controls.

## Reporting Security Issues

Do not disclose suspected vulnerabilities publicly before maintainers have reviewed them. Open a private security advisory or contact the maintainers through the repository's preferred private channel when available.

Include:

- A concise description of the issue.
- The affected document, diagram, standard, or proposed architecture.
- The security principle or control that may be violated.
- Suggested remediation when known.

## Documentation Security Standards

Security-sensitive documentation must:

- Identify trust boundaries.
- Distinguish users, organizations, tenants, services, agents, and external systems.
- Avoid hard-coded secrets, credentials, private endpoints, or operationally sensitive values.
- Describe data classification and retention expectations when relevant.
- Consider prompt injection, tool misuse, connector abuse, model output handling, and tenant isolation for AI-native features.

## Supported Versions

The current supported documentation version is `v0.1.0`.

