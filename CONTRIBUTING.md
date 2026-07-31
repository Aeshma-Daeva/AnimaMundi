# Contributing

Anima Mundi is currently a tightly controlled research program rather than an open feature marketplace. Contributions are welcome when they preserve the distinction between mechanics, observation, interpretation, and infrastructure.

## Good first contributions

- documentation and diagrams;
- reproducibility checks on a declared environment;
- test isolation and performance profiling;
- read-only analysis of already sealed artifacts;
- visualization that cannot feed back into mechanics;
- review of conservation, rollback, provenance, or statistical contracts.

## Before proposing a mechanics change

Open an issue describing:

- the exact causal route;
- the state fields it owns;
- conservation implications;
- checkpoint and rollback behavior;
- matched controls;
- what observation would falsify the intended effect;
- semantic claims that the mechanism does *not* authorize.

Do not submit a mechanics change that simultaneously changes the observer or success criteria.

## Pull requests

A pull request should include:

- concise motivation;
- affected architectural layer;
- tests and exact commands;
- deterministic or numerical-equivalence expectations;
- artifact/schema compatibility notes;
- `scientific mechanism changed: yes/no`.

## Current priority

The active priority is physical-host qualification and the frozen one-shot campaign. Unrelated mechanism expansion may be deferred until that evidence is complete.
