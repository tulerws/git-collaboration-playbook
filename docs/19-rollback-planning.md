# Rollback planning

Plan rollback before deployment, while the change and its dependencies are
still fresh.

- Identify the last known-good version.
- Check whether data changes are backward compatible.
- Separate application rollback from configuration rollback.
- Define the signal and decision owner for reverting.
- Test the rollback path for high-risk releases.

A rollback that loses data is a recovery procedure and should be labeled as one.
