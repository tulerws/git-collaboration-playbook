# Database migrations

Design migrations so old and new application versions can overlap safely.

- Add compatible structures before code depends on them.
- Backfill large datasets in bounded batches.
- Measure locks and execution time on representative data.
- Delay destructive cleanup until the new version is stable.
- Keep a verified backup and recovery procedure.

Fail clearly when a required schema version is missing.
