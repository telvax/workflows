<p align="center">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="assets/symbol-dark.svg">
<img src="assets/symbol-light.svg" alt="The Telvax symbol: a T made of a 2 by 3 tensor between brackets" width="120">
</picture>
</p>

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

## License

Dual-licensed under MIT (`LICENSE-MIT`) or Apache 2.0 (`LICENSE-APACHE`), at your option.
