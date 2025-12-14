# Scan Spine Protocol

## Purpose
Defines how a system introspects itself safely.

Scan Spine provides **bounded self-observation**.

## Scan Scope
A scan may observe:
- State summaries
- Transition counts
- Boundary conditions

A scan may NOT:
- Rewrite state
- Trigger transitions
- Modify rules

## Frequency
Scans must be:
- Periodic
- Rate-limited
- Logged

## Output
Scan results feed:
- Diagnostics
- Evaluation
- Human oversight

Unbounded introspection is prohibited.
