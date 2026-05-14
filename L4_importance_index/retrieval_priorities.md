# Retrieval Priorities (L4)

This file guides how context should be fetched for different types of prompts.

The LLM should keep this aligned with current project focus and importance scores.

## Prompt Type → Retrieval Strategy

**Architecture / Foundational Questions**
- Priority: L1 (if touches invariants) → L2 high-stability sections → L4 relationships

**Implementation / Code-level**
- Priority: Relevant L2 module understanding → Specific L3 if needed → Avoid full repo unless debugging

**Decision Review**
- Priority: Decision records in L2 + related L4 links + relevant episodic context from L3

**New Information Integration**
- Priority: Current mental model (L2) + high-relevance sections + check against L1

**General / Exploratory**
- Priority: L2 abstractions + high importance scores from L4

*Update this file as project focus shifts and as you learn what retrieval patterns work best.*