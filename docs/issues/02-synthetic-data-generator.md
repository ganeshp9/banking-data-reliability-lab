# Build deterministic synthetic-data generation

## Objective

Generate reproducible daily snapshots, transaction events, reference data, and
source manifests with controlled defect injection.

## Acceptance criteria

- [ ] A documented seed reproduces the same clean dataset.
- [ ] CSV snapshots and JSON events conform to their contracts.
- [ ] Manifests contain expected files, record counts, and control totals.
- [ ] Defect scenarios include late, duplicate, missing, invalid, drifted, unmatched, and incorrect-total data.
- [ ] Tests verify determinism and each injected defect.

## Out of scope

Real banking data and production-scale volume claims.
