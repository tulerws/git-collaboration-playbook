# Security review

Treat authentication, authorization, secrets, and untrusted input as explicit
review areas.

- Confirm authorization at the server-side boundary.
- Avoid logging credentials or sensitive payloads.
- Validate and constrain external input.
- Pin or review changes to security-sensitive dependencies.
- Use private reporting channels for suspected vulnerabilities.

Never place real secrets in commits, examples, fixtures, or screenshots.
