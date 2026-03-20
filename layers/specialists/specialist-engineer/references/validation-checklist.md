# Engineering Validation Checklist

Choose the lightest set of checks that can still falsify the change.

## Common Options

- Unit tests for changed logic.
- Integration tests for boundaries, contracts, or persistence.
- Type checking and linting for static correctness.
- Manual reproduction of the bug before and after the fix.
- Build or packaging checks when the output artifact matters.

## Reporting

- State exactly what you ran.
- State what you could not run.
- State the remaining risk in one sentence.

## Escalation Triggers

- Schema or API contract changes.
- Auth, permissions, payments, or destructive operations.
- Large refactors without strong automated coverage.
