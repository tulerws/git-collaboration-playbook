# Merge strategies

Choose the merge strategy based on the history the repository wants to keep.

- **Squash:** one concise commit per pull request.
- **Merge commit:** preserves the complete branch structure.
- **Rebase:** preserves individual commits without a merge commit.

Do not change strategy only to work around failing checks. Resolve the failure,
then merge using the repository's normal convention.
