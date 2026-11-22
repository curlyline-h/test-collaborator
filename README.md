# Calculator

A small Python calculator module used to demonstrate code review with SmartBear Collaborator and its GitHub and Jira integrations.

## Features

- `add(a, b)`
- `subtract(a, b)`
- `multiply(a, b)`
- `divide(a, b)` (raises an error on division by zero)

## Usage

```bash
python calculator.py
```

Expected output:

```
2 + 3 = 5
5 - 2 = 3
4 * 3 = 12
10 / 2 = 5.0
```

## Review workflow

1. New changes are made on a separate branch.
2. A pull request is opened on GitHub.
3. The pull request is reviewed in Collaborator, where reviewers comment and log defects.
4. Defects that need tracking are sent to Jira as issues.
5. The author fixes the defects, the reviewer verifies them, and the pull request is merged.
