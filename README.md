# Krafton Final myjob GitOps polling fixture

This repository is a small fixture for checking GitHub polling and manifest diff handling from another project.

The manifest under `deploy/sandbox/demo-app.yaml` is intentionally simple and sandbox-scoped so polling code can compare commit-to-commit changes without touching a real cluster.

Useful checks:

- changed manifest discovery from `deploy/**`
- Deployment image and replica diffs
- ConfigMap data diffs
- Service port diffs

some xhages?
