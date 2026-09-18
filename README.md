# Self-Hosted AI Deployment Patterns

Documentation of deployment concerns for AI-assisted workflows: service boundaries, scheduled tasks, access controls, validation gates and operational risk.

## Public scope

Patterns and sanitized diagrams only. No server addresses, credentials, private routes or production files.

## Operating pattern

```text
Service boundary -> access control -> scheduled work -> validation gate -> logs and review
```

The package focuses on the operational questions around AI systems: how they are accessed, checked, monitored and handed over.

Architecture source: `architecture.mmd`.

## Review points

- TLS and restricted administration as deployment controls.
- Scheduled jobs and service boundaries.
- Validation gates and known failure states.
- Explicit distinction between documented controls and unresolved production risks.

## Reproducibility

This package is documentation-first. It should be published with a sanitized architecture diagram and a local deployment decision record; private infrastructure must remain excluded.

## Related case study

See `../case-studies/05-self-hosted-ai-deployment.md` in the portfolio source.
