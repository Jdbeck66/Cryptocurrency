---
name: new-section
description: Create a new markdown content section following project standards
disable-model-invocation: true
argument-hint: [section-number] [topic-title]
---

Create a new section file at `sections/$ARGUMENTS[0].md` with the title "$ARGUMENTS[1]".

Follow these content standards:

## Structure
- Start with `# Section N: Title`
- Include a Table of Contents with anchor links
- Use numbered subsections (N.1, N.2, etc.)
- End with Key Takeaways, Further Reading, and Computational Exercises

## Formatting Requirements
- Define all technical terms in callouts:
  ```
  > **Definition: Term**
  >
  > Clear explanation.
  ```
- Expand all acronyms on first use: Full Name (ACRONYM)
- Cite sources: **Source:** Author. (Year). Title. URL
- Cross-reference relevant notebooks in `notebooks/` directory
- Use comparison tables for contrasting concepts
- Include concrete numerical examples and mathematical formulas where relevant

## Quality Standards
- Build from basic definitions to advanced technical details
- Use concrete examples before abstraction
- Connect historical context to modern implementations
- Explain common conceptual hurdles explicitly
- Aim for 800-1500 lines of comprehensive educational content
