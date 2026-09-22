# Orchestrate workflows and recovery

## Objective

Use Airflow to coordinate dependencies, retries, backfills, and correction
workflows without hiding failures.

## Acceptance criteria

- [ ] The DAG separates generation, ingestion, validation, transformation, and reconciliation.
- [ ] Dependencies and retry behaviour are explicit.
- [ ] One late-file scenario can be recovered safely.
- [ ] One corrected-data backfill is demonstrated.
- [ ] Reruns preserve idempotency and quality evidence.

## Out of scope

Managed Airflow services and multi-cloud orchestration.
