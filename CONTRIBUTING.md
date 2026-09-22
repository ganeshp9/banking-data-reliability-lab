# Contributing

This project uses an issue-first workflow so that every change has a stated
purpose, bounded scope, and testable acceptance criteria.

## Before starting work

1. Search the open Issues for an existing milestone or defect.
2. Create or refine an Issue before writing code.
3. Confirm the acceptance criteria and identify any dependencies.
4. Keep the change focused on one Issue.

## Branches and commits

- Branch from `main` using `feature/<issue-number>-short-name`,
  `fix/<issue-number>-short-name`, or `docs/<issue-number>-short-name`.
- Write imperative commit subjects, for example:
  `Add customer data contract validation`.
- Do not commit real customer data, credentials, `.env` files, generated data,
  employer code, proprietary schemas, or confidential logic.

## Pull requests

A pull request should:

- link its Issue with `Closes #<number>`;
- explain the problem and the chosen approach;
- include or update tests for behavioural changes;
- document setup, schema, or operational changes;
- pass formatting, linting, and automated tests; and
- remain small enough to review without unrelated refactoring.

## Data and quality expectations

- Use deterministic synthetic fixtures and document their seed.
- Preserve source lineage and machine-readable failure reasons.
- Test successful paths, invalid inputs, reruns, and recovery behaviour.
- Never silently discard rejected records.
- Do not make performance or reliability claims without reproducible evidence.

## Local checks

The exact commands will be activated with the first implementation milestone.
The intended interface is:

```bash
ruff check .
ruff format --check .
mypy src
pytest
```
