bibtex-tidy mirror
==================

Mirror of bibtex-tidy package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For bibtex-tidy: see https://github.com/FlamingTempura/bibtex-tidy


### Using bibtex-tidy with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/njzjz/mirrors-bibtex-tidy
    rev: ''  # Use the sha / tag you want to point at
    hooks:
    -   id: bibtex-tidy
```
