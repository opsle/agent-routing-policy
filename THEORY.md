# Theory

## Observation

Opaque routing can violate provider budgets, reviewer independence, access boundaries, or exact model/profile constraints.

## Hypothesis

A vendor-neutral policy that emits a durable structured reason can make adaptive and strict routes auditable and safely enforceable.

## Proposed mechanism

Filter and rank by task capability, role, project access, allowlists/exclusions, availability, model/profile, preference, price, empirical performance, purpose, reviewer independence, and fallback eligibility; support strict immutable route envelopes.

## Falsifiable requirements

1. Every route produces a durable structured reason.
2. Strict authorization is checked before provider process or credential exposure where possible.
3. Provider availability is revisioned evidence.
4. Forbidden alternatives remain forbidden.

## Disconfirming results

The hypothesis should be weakened or rejected if a comparable baseline passes the same correctness gate and this mechanism provides no repeatable benefit, or if the mechanism introduces safety/correctness failures that bounded revisions do not resolve. Negative results remain in `experiments/`.

## Uncertainty

Quality-adjusted price experiments, comparable provider benchmarks, policy portability, and fairness/stability analysis.
