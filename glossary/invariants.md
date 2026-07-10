# Invariants (DSLO Glossary)

## Definition
Invariants are **non‑negotiable semantic constraints** that must remain true across all system states, transformations, refactorings, and agent‑mediated modifications. They encode the stable meaning of a domain.

In DSLO, invariants form the **Semantic Invariant Layer**, the first and most critical layer of the substrate.

## Purpose
- Preserve domain meaning across time.
- Prevent semantic drift during AI‑accelerated development.
- Provide machine‑readable semantic boundaries.
- Anchor deterministic execution semantics.

## Properties
- Deterministic  
- Contextless  
- Machine‑enforceable  
- Non‑probabilistic  
- Stable across iteration  

## Examples (Conceptual)
- “A customer must have exactly one identity.”
- “A ledger entry cannot mutate after creation.”
- “A semantic boundary cannot be crossed without an invariant gate.”

## DSLO Cross‑Reference
See **FIELD_DEFINITION.md → Section 5.1 (Semantic Invariant Layer)**.
