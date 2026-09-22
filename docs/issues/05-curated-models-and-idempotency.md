# Build curated models and idempotent processing

## Objective

Publish trustworthy customer, account, transaction, and daily-balance models
using SQL and targeted PySpark transformations.

## Acceptance criteria

- [ ] Curated schemas and transformation decisions are documented.
- [ ] Identifiers, timestamps, currencies, and status values are standardized.
- [ ] Identical reruns produce no duplicate curated records.
- [ ] Incremental processing and required history behaviour are tested.
- [ ] PySpark is used only where its distributed behaviour is demonstrated.

## Out of scope

Unjustified large-scale or performance claims.
