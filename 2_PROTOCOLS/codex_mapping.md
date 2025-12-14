# Codex Mapping Protocol

## Purpose
Codex Mapping ensures **semantic alignment** between:
- Theory terms
- Protocol definitions
- Implementation labels

## Mapping Rules

1. Every operational term must map to a canonical definition
2. No synonym proliferation
3. No silent redefinition

## Example

| Canonical Term | Allowed Operational Alias |
|--------------|--------------------------|
| Flame Line | activation_path |
| Hollow Node | boundary_state |

## Drift Detection
Any divergence between usage and canonical definition must be flagged.

Semantic drift is treated as a system fault.
