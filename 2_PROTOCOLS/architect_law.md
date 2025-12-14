# Architect Law

## Purpose
Architect Law defines **structural invariants** that any compliant system must satisfy.

It governs *how systems are allowed to be built*.

## Core Laws

### Law 1 — Directed Structure
All system transitions must be directionally well-defined.
No ambiguous or bidirectional causality without explicit mediation.

### Law 2 — Boundary Integrity
Every subsystem must declare:
- Entry conditions
- Exit conditions
- Collapse conditions

### Law 3 — Non-Recursive Authority
No component may unilaterally redefine the rules that govern it.

### Law 4 — Observability
All critical transitions must be externally observable or logged.

## Enforcement
Violations invalidate protocol compliance.

Architect Law is **non-negotiable**.
