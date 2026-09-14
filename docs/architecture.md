# FIRSTLIGHT Architecture

FIRSTLIGHT models the first coordinated phase of critical incident response.

## Flow

```text
INCIDENT SIGNAL
      │
      ▼
 INITIAL STATE
      │
      ├── FACTS
      ├── CONSTRAINTS
      ├── OWNERS
      └── FIRST ACTIONS
             │
             ▼
      COORDINATED RESPONSE
             │
       ┌─────┼─────┐
       ▼     ▼     ▼
     TRACE BLACKBOX RECOVER
             │
             ▼
            WAKE
```

## Design principles

1. First actions must be explicit.
2. Facts, assumptions, and decisions remain distinguishable.
3. Parallel work is coordinated without hiding ownership.
4. Every handoff preserves context.
5. Escalation is driven by state, not noise.