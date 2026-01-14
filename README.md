gofumpt mirror
================

Mirror of gofumpt golang linter for pre-commit. Created with [pre-commit-mirror-maker](https://github.com/pre-commit/pre-commit-mirror-maker).

For pre-commit: see https://github.com/pre-commit/pre-commit

For gofumpt: see https://github.com/mvdan/gofumpt

### Using gofumpt with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/mxr/mirrors-gofumpt
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: gofumpt
```
