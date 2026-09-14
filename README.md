# FIRSTLIGHT

**First-hour incident orchestration.**

> What should happen first?

FIRSTLIGHT explores the coordination layer for the opening phase of a critical incident: establish facts, assign initial actions, protect the system, and create a controlled path into deeper response.

## Why it exists

The first phase of an incident is often dominated by incomplete information and competing priorities.

FIRSTLIGHT makes the opening response explicit: **what is known, what must happen first, who owns it, and what context must be handed forward.**

## Core responsibilities

- establish initial incident state
- sequence first-response actions
- coordinate parallel workstreams
- record decisions and assumptions
- hand off into investigation and recovery

## Use cases

| Use case | Question answered |
| --- | --- |
| Incident intake | What is the initial state? |
| First-hour coordination | What should happen first? |
| Ownership | Who is responsible for each action? |
| Parallel response | Which workstreams can proceed together? |
| Handoff | What context must move into TRACE, BLACKBOX, or RECOVER? |

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