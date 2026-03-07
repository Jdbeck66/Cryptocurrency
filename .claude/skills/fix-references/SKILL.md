---
name: fix-references
description: Scan all sections for notebook cross-references and fix them to match the canonical notebook list in CLAUDE.md
disable-model-invocation: true
---

Fix notebook cross-references across all section files to match the canonical notebook plan.

## Process

1. Read `CLAUDE.md` to get the authoritative notebook list (names and numbers)
2. Read each file in `sections/` directory
3. Find all references to notebooks (patterns like `notebooks/NN-name.ipynb`, backtick-quoted notebook names, or prose references to notebook numbers)
4. Compare each reference against the canonical list
5. Fix mismatches:
   - Wrong notebook number for a topic → correct the number
   - Wrong notebook name → correct the name
   - References to notebooks that don't exist → map to the correct notebook or flag for review
   - "(upcoming)" annotations should remain on notebooks not yet complete
6. Report all changes made

## Rules
- Never change the canonical list in CLAUDE.md — that is the source of truth
- Preserve the surrounding prose context when fixing references
- If a section references content that doesn't map to any planned notebook, flag it rather than silently removing
- Update both the Computational Exercises section and any inline notebook references within the section body
