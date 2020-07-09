# mirrors-shellcheck

Mirror of shellcheck for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For shellcheck: see https://github.com/koalaman/shellcheck

### Using shellcheck with pre-commit:

Add this to your `.pre-commit-config.yaml`

```yaml
-   repo: https://github.com/5xops/mirrors-shellcheck
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: shellcheck
```
