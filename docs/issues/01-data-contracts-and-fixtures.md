# Define data contracts and representative fixtures

## Objective

Define versioned contracts for customers, accounts, transactions, institutions,
and service mappings before pipeline code is written.

## Acceptance criteria

- [ ] Every dataset documents its fields, types, keys, nullability, ranges, and timestamps.
- [ ] Relationships and referential-integrity expectations are explicit.
- [ ] Sensitive-field treatment confirms that all examples are synthetic.
- [ ] Valid and deliberately invalid sample records are committed.
- [ ] Contract validation has automated tests.

## Out of scope

Generation at scale, ingestion, transformation, and orchestration.
