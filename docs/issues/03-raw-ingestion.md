# Implement immutable raw ingestion

## Objective

Load source files and events with run metadata and source lineage while
preserving the received records.

## Acceptance criteria

- [ ] Each run receives a unique run ID and timestamps.
- [ ] Raw records retain source file or event lineage.
- [ ] Repeat ingestion is safe and does not duplicate registered inputs.
- [ ] Malformed inputs fail visibly with actionable errors.
- [ ] Unit and integration tests cover clean and failed ingestion.

## Out of scope

Curated business tables and dashboarding.
