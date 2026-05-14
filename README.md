# Brain System — Dynamic Plastic Memory Architecture (DPMA)

**Status**: Complete foundational implementation  
**Architecture Version**: 2.0 (Dynamic Plastic Memory Architecture)

This folder is the live implementation of the **Dynamic Plastic Memory Architecture (DPMA)** — a 5-layer, self-organizing, brain-inspired memory system for persistent LLM collaboration.

## Purpose

Provide long-term memory, selective context retrieval, strong protection of core invariants, and high plasticity for reorganization — without context bloat or rigid structures.

## How to Use This System

### For LLMs / Agents
- Treat this entire folder as your persistent external memory.
- Follow the **consolidation workflow** after significant work or when requested.
- Use **L4 (Importance Index)** as your primary guide for what to load.
- Never modify L1 without following the strict Change Proposal protocol.
- Freely create files and structure inside L2 as your understanding evolves.

### Quick Commands / Triggers
- "Perform consolidation on the brain system"
- "Update importance scores and reorganize L2"
- "Review core invariants with change proposal"
- "Load relevant context from brain_system using DPMA"

## Layer Structure

| Layer | Folder                        | Purpose                                      | Mutability     | Key Files |
|-------|-------------------------------|----------------------------------------------|----------------|-----------|
| **L1**    | `L1_core_invariants/`        | Fundamental, protected principles            | Extremely Low  | `core_principles.md`, `change_proposal_template.md` |
| **L2**    | `L2_semantic_architecture/`  | LLM's organized understanding & abstractions | High           | `current_mental_model.md`, `key_abstractions.md`, `patterns_and_anti_patterns.md`, `architecture_decisions.md` |
| **L3**    | `L3_episodic_memory/`        | Specific events, sessions, raw details       | High           | Session logs, experiment notes |
| **L4**    | `L4_importance_index/`       | Scores, relationships, retrieval priorities  | Medium-High    | `master_importance_index.md`, `retrieval_priorities.md`, `relationship_graph.md` |
| **L5**    | `L5_meta_cognition/`         | System self-reflection & optimization        | Medium         | `consolidation_history.md`, `self_optimization_notes.md` |

## Core Operating Rules (from DPMA)

- **L1 is sacred** — Changes require multi-stage evaluation (Impact → Consistency → Plasticity Cost → Proposal). Default: 90% resistive.
- **Plasticity via L4** — Reorganize primarily by updating scores, tags, and relationships rather than moving text.
- **LLM self-structuring** — You have full authority to design the best structure inside L2.
- **Importance-aware retrieval** — Always start from L4 when deciding what context to load.
- **No limits** — Create as many files and folders as needed for clarity and retrieval quality.

## Getting Started

1. Read `../brain_system_architecture.md` for the full theoretical design.
2. Review `L1_core_invariants/core_principles.md`.
3. Begin using the system. Trigger consolidation when ready.
4. Maintain L4 diligently — it is the key to efficient retrieval and plasticity.

---
*This system is designed to improve over time through repeated consolidation and self-optimization.*