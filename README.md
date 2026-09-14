# FIRSTLIGHT

**First-hour incident orchestration.**

> What should happen first?

FIRSTLIGHT explores the coordination layer for the opening phase of a critical incident: establish facts, assign initial actions, protect the system, and create a controlled path into deeper response.

## Core responsibilities

- establish initial incident state
- sequence first-response actions
- coordinate parallel workstreams
- record decisions and assumptions
- hand off into investigation and recovery

## Architecture

```text
INCIDENT SIGNAL
      │
      ▼
INITIAL STATE
      │
      ├──► FIRST ACTIONS
      ├──► OWNERS
      ├──► SAFETY / CONSTRAINTS
      └──► CONTEXT
              │
              ▼
       COORDINATED RESPONSE
              │
              ▼
       TRACE / BLACKBOX / RECOVER
```

## Ecosystem

FIRSTLIGHT sits between incident understanding and human/system response, connecting investigation to coordinated action.

## Status

Early research and architecture.

- [Architecture](docs/architecture.md)
- [Roadmap](docs/roadmap.md)

## License

MIT.