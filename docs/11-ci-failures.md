# CI failure triage

Start from the first relevant failure rather than the final cascade.

1. Identify the failing job, step, and exact command.
2. Decide whether the failure reproduces locally.
3. Separate deterministic failures from infrastructure flakiness.
4. Fix the root cause and rerun the smallest relevant check.
5. Confirm the complete required workflow before merging.

Do not repeatedly rerun a deterministic failure without changing anything.
