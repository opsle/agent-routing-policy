# Benchmark plan

## Rule zero: correctness gate

Efficiency results are comparable only when every candidate passes the same deterministic correctness and safety gates. Incorrect, indeterminate, and policy-violating runs remain visible but are excluded from superiority claims.

## Baselines

1. Current conventional mechanism without this project.
2. The narrowest deterministic alternative.
3. This project at an exact revision and configuration.

## Measurements

- route correctness
- constraint violations
- quality
- price
- fallback/retry outcomes
- reason reproducibility

## Repetition and reporting

Record model, provider, model version, reasoning effort, tool versions, fixture, prompt, environment/hardware, repetition count, observable tool activity, final result, correctness, cost/tokens when available, and known confounders. Report distributions and raw observations; never invent missing values.

## Adversarial cases

- Attempt to violate: Every route produces a durable structured reason.
- Attempt to violate: Strict authorization is checked before provider process or credential exposure where possible.
- Attempt to violate: Provider availability is revisioned evidence.
- Attempt to violate: Forbidden alternatives remain forbidden.

## Result policy

Retain positive, negative, null, and failed experiments. Update maturity only when the actual stated hypothesis has reproducible evidence.
