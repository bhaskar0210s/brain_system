# Master Importance Index

This file (or additional files in this folder) tracks importance, stability, and relationships across the brain system.

The LLM maintains and updates scores during consolidation.

## Scoring Dimensions (suggested)

- **Stability**: How fundamental / core-like this knowledge is (0-100). High scores lean toward L1.
- **Relevance**: Current importance to active projects (0-100)
- **Usage**: How often this has been retrieved/used recently
- **Generality**: How widely applicable across contexts (0-100)
- **Confidence**: How well-established this knowledge is

## Example Entry Format

```markdown
### Knowledge Item: [Short name or link]

**Location**: L2_semantic_architecture/xxx.md#section
**Stability**: 71/100
**Relevance**: 93/100
**Usage**: High
**Generality**: 65/100
**Last Updated**: 2026-05-14
**Relationships**: Supports X, Contradicts Y (weakly)
**Notes**: 
```

The LLM should evolve the best format for tracking and retrieval.