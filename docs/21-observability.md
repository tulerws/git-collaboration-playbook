# Observability

Instrumentation should explain whether a change is healthy after deployment.

- Emit structured logs with stable event names.
- Track latency, traffic, errors, and resource saturation.
- Add correlation identifiers across service boundaries.
- Alert on user impact rather than isolated implementation details.
- Link dashboards and runbooks from release notes when relevant.

Avoid recording secrets or unnecessary personal data in telemetry.
