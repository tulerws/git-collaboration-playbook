# Feature flags

Treat each feature flag as temporary operational code.

- Define its owner and removal condition before rollout.
- Keep the disabled path safe and tested.
- Avoid combining unrelated behavior under one flag.
- Monitor both variants during gradual exposure.
- Remove the flag after the rollout decision is complete.

Document whether changing the flag requires a restart or takes effect live.
