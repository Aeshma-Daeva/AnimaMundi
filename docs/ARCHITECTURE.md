# Architecture

Anima Mundi is separated into four layers so that engineering convenience cannot silently become scientific causation.

## 1. Mechanics

World state, conserved resources, recurrent capsule dynamics, bodies, heredity, weather, basins, packets, and transit.

Mechanics are deterministic under the declared environment and ordering contracts. Changes require conservation, finite-state, rollback, checkpoint, matched-control, and replay gates.

## 2. Operational history

Append-only records of what the mechanics did: lifecycle events, lineage, manipulation attempts, basin transitions, weather, packets, launches, arrivals, accounting, and provenance.

Operational history is not allowed to feed back into mechanics merely because it has been recorded.

## 3. Observation and interpretation

Read-only natural-history, longitudinal, deep-sentinel, and replay observers consume sealed state and history. Before/after witnesses prove observation does not alter the world.

Interpretation remains bounded. Terms such as life, agency, identity, cooperation, or ontological death are not inferred from event names.

## 4. Execution substrate

The cohort executor manages independent seeded cells:

```text
frozen plan
  → simulation queue
  → isolated one-thread process
  → completed-unverified artifact
  → verification queue
  → verified promotion or quarantine
```

Completed processes release their complete RSS to the operating system. Verification does not hold a simulation slot. Restart recovery is bound to task identity, attempt identity, process groups, checkpoints, and canonical digests.

## Scale hierarchy

- substrate patches and fields;
- recurrent capsules and couplings;
- bodies and topology;
- lineages and relationships;
- candidate worlds and basins;
- archipelagos;
- cross-world dispersal;
- independent seeded simulation cells;
- verified comparative cohorts.

Parallelism occurs across independent cells, not by allowing many threads to mutate one universe concurrently.
