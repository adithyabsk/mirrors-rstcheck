rstcheck mirror
===============

Mirror of rstcheck gem for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit
For rstcheck: see https://github.com/myint/rstcheck


### Using rstcheck with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: https://github.com/adithyabsk/mirrors-rstcheck
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: rstcheck
            args: [-r DIRECTORY_NAME]

**Based on**: https://github.com/pre-commit/mirrors-ruby-lint