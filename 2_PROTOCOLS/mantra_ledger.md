# Mantra Ledger Protocol

## Purpose
Defines how systems persist **state, intent, and historical commitments**.

A Mantra is a minimal declarative record of:
- What was intended
- What was done
- What was learned

## Ledger Structure
Each entry must include:
- Timestamp
- Actor
- Action
- Outcome
- Context reference

## Properties
- Append-only
- Tamper-evident
- Queryable

## Failure Handling
Ledger corruption invalidates downstream results.

Memory is a protocol, not an accident.
