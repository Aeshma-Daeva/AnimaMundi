# Publication Scope

This repository initially publishes the project control surface: status, roadmap, architecture, research boundaries, contribution policy, and the current sealed verification claims.

The executable research snapshot and large historical evidence payloads are intentionally not being pushed blindly into public Git history. They should be added after a dedicated privacy, licensing, and repository-structure review.

## Planned source publication

The next publication PR should add:

- the Python engine and CLI;
- tests for the fractal worlds, cohort executor, and one-shot campaign;
- RunPod qualification and campaign scripts;
- current schemas, manifests, and verification summaries;
- no virtual environments, caches, ephemeral checkpoints, or personal infrastructure data.

## Historical evidence

Multi-megabyte ledgers and imported evidence baselines should be distributed as versioned release assets or external archives rather than ordinary Git files. Their manifests remain part of the reproducibility contract.

No excluded or absent artifact should be silently regenerated or replaced.
