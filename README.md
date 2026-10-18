# Shared workflows

Reusable GitHub Actions workflows (`on: workflow_call`) for the repositories in this organization, so a rule is written once.

Use one from another repository with:

```yaml
jobs:
  checks:
    uses: telvax/workflows/.github/workflows/<name>.yml@main
```

## Status

No workflow here yet. The ones in use (`update-branches`, `dependabot-auto-merge`, `secrets`) are in [telvax/telvax](https://github.com/telvax/telvax) and move here only when a second repository needs them.
