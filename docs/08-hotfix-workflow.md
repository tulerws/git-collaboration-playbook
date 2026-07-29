# Hotfix workflow

Use a hotfix only for a production-impacting problem that cannot wait for the
normal release cycle.

1. Branch from the exact production revision.
2. Make the smallest safe correction.
3. Add a regression test when practical.
4. Obtain focused review and run required checks.
5. Deploy, verify, and merge the fix back into active development branches.

Document follow-up work separately instead of expanding the emergency change.
