# Contributing

## Workflow

1. Keep changes focused and update the README if behavior or usage changes.
2. Prefer small, reviewable commits.
3. Avoid checking in local editor, IDE, or OS files.

## Repo structure

- `README.md` documents the install and troubleshooting flow.
- `helm-values/` contains Helm overrides.
- `manifests/` contains Kubernetes and AWS-related YAML/JSON manifests.

## Before submitting

- Verify manifests and values files match the README instructions.
- Ensure new files are added to `.gitignore` only when they are local-only artifacts.
