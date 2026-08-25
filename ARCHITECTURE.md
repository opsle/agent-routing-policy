# Architecture

```text
generic input → Agent Routing Policy → generic output
```

## Ports

- Input adapter: translates a host’s observable state into the generic contract.
- Core: deterministic policy/mechanism under test.
- Evidence store: immutable or append-only artifacts where required.
- Output adapter: returns a bounded receipt to the host.

## Independence

Host-specific adapters are optional and removable. Disabling the project should return the host to its prior behavior. No core module may import Taslos Tasks internals.
