pep8 pre commit

### Using pep8 with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git@github.com:mad01/pre-commit-pep8
        sha: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: pep8
            args: [--max-line-length=120]
