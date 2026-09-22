# Add quality gates and quarantine

## Objective

Prevent invalid data from reaching curated tables and preserve every rejected
record with a machine-readable reason.

## Acceptance criteria

- [ ] Checks cover completeness, validity, uniqueness, consistency, freshness, and referential integrity.
- [ ] Blocking failures prevent publication to curated tables.
- [ ] Every rejection includes run ID, source lineage, check name, and reason code.
- [ ] Seeded blocking defects are detected by automated tests.
- [ ] Corrected records can be reprocessed without losing failure history.

## Out of scope

Business fraud rules, credit scoring, and regulatory certification.
