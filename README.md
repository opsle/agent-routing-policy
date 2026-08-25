# Agent Routing Policy

> Experimental Opsle research. Claims are hypotheses until evidence supports them.

## Problem

Opaque routing can violate provider budgets, reviewer independence, access boundaries, or exact model/profile constraints.

## Hypothesis

A vendor-neutral policy that emits a durable structured reason can make adaptive and strict routes auditable and safely enforceable.

## Mechanism

Filter and rank by task capability, role, project access, allowlists/exclusions, availability, model/profile, preference, price, empirical performance, purpose, reviewer independence, and fallback eligibility; support strict immutable route envelopes.

## Why it matters

The Opsle thesis asks: **What if we stopped using intelligence for work that doesn’t require intelligence?** This project isolates one candidate boundary so it can be falsified and measured independently.

## Non-goals

Claiming desired routes are implemented, universal cheapest-model routing, or probing credentials before authorization.

## Current maturity

**THEORY** under the [Opsle maturity model](https://github.com/opsle/research/blob/main/MATURITY.md).

## Existing evidence

Capability/project routing and strict controlled provider/review constraints demonstrate feasibility in one system.

## Evidence still missing

Quality-adjusted price experiments, comparable provider benchmarks, policy portability, and fairness/stability analysis.

## Benchmark strategy

Correctness gates every comparison. Planned measures:

- route correctness
- constraint violations
- quality
- price
- fallback/retry outcomes
- reason reproducibility

See [BENCHMARK.md](BENCHMARK.md) for experiment rules. No benchmark numbers are claimed.

## Relationship to other Opsle research

This project is part of [Opsle Research](https://github.com/opsle/research). Opsle Tasks is the future public name of the integrated reference system from which several ideas emerged. Its active development migration to the Opsle organization is intentionally deferred.

## Relationship to future Opsle Tasks

Future Opsle Tasks may consume this project through an adapter only after evidence supports integration. The active predecessor, Taslos Tasks, remains unchanged and has no dependency on this repository.

## Installation status

No installable production package is justified yet. The repository is theory/specification-first.

## Known limitations

Quality-adjusted price experiments, comparable provider benchmarks, policy portability, and fairness/stability analysis.

## License

Apache-2.0. See [LICENSE](LICENSE).
