# Project Status

**Updated:** 2026-07-30  
**Current phase:** `S3.1 — capture physical host`  
**Release state:** sealed dynamic RunPod package prepared; scientific campaign not yet executed

## Current reference

The current execution reference combines:

- private rollback-state images rather than public checkpoint construction on every successful tick;
- exact public checkpoint and operational-history witnesses;
- isolated single-threaded scientific cells;
- deterministic task and plan identity;
- separate simulation and verification queues;
- live RSS/PSS and cgroup-aware admission;
- restart recovery, quarantine, and atomic canonical promotion;
- an unbiased 128-tick primary census and a separate conditional succession lane.

## Latest verification

| Surface | Result |
|---|---:|
| Complete fractal + one-shot | 161 passed, 1 optional skip, 0 failed |
| Curated evidence | 105/105 |
| Repository-wide | 361 passed, 1 skipped, 2 known historical failures |
| Seal manifest | 327 files verified |

## Known historical conditions

1. A legacy agency digest differs in the transferred unpinned Python 3.13 / NumPy 2.3 environment. The historical digest was not rewritten.
2. A historical sealed v2.5.2 challenge artifact is absent from the transferred archive. It was not regenerated or substituted.

Neither condition is a failure of the sealed rollback, executor, or dynamic campaign substrate.

## Exact next action

On the physical host:

```bash
python scripts/oneshot128_campaign.py validate
python scripts/capture_substrate128_host.py \
  --out "$WORKSPACE/oneshot128/qualification/SUBSTRATE_128_HOST_INVENTORY.json"
python scripts/verify_substrate128_host.py \
  --inventory "$WORKSPACE/oneshot128/qualification/SUBSTRATE_128_HOST_INVENTORY.json"
```

The production worker count remains unauthorized until the real CPU, SMT, NUMA, RAM, cgroup, and storage topology is measured.
