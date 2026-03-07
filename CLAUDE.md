# Cryptocurrency Education Project

## Purpose

Replicate MIT Sloan's "Blockchain and Crypto Applications: From Decentralized Finance to Web 3" course using entirely open-source resources. All content must be rigorously sourced and documented.

Course reference: MIT Sloan Blockchain and Crypto Applications Online Short Course

## Environment

- **Conda env:** `blockchain-module1` (activate with `conda activate blockchain-module1`)
- **Prefer mamba** over conda for all package/environment operations
- **Python:** 3.11
- **Environment file:** `environment.yml` at project root
- **Notebooks run in:** JupyterLab

## Project Structure

```
Cryptocurrency/
├── CLAUDE.md              # This file - project config, status, standards
├── README.md              # Course overview and learning paths
├── environment.yml        # Single project-wide mamba/conda environment
├── notebooks/             # Jupyter notebooks (sequential, flat)
│   ├── 01-cryptographic-primitives.ipynb
│   ├── 02-bitcoin-blockchain-analysis.ipynb
│   └── ...
└── sections/              # Markdown content sections (sequential, flat)
    ├── 01-historical-evolution.md
    ├── 02-bitcoin-deep-dive.md
    └── ...
```

## Content Standards

### Markdown Sections
- All technical terms defined in markdown callouts (`> **Definition: Term**`)
- All acronyms expanded on first use: Full Name (ACRONYM)
- Comprehensive source citations: **Source:** Author. (Year). Title. URL
- Clear progression from foundational concepts to advanced details
- Cross-references to relevant notebooks
- End with Key Takeaways, Further Reading, and Computational Exercises

### Jupyter Notebooks
- Title cell with overview, learning objectives, prerequisites, estimated time
- Theory explanation in markdown cells before code
- Clear comments in code cells
- Executable examples with output demonstrations
- Exercises section with starter code
- Summary and next steps at the end

### Pedagogical Approach
- Build from basic definitions to advanced technical details
- Use concrete examples and step-by-step math before abstraction
- Connect historical context to modern implementations
- Use real-world data and statistics where possible
- Explain common conceptual hurdles explicitly (e.g., "computationally infeasible" vs "impossible")

## Progress

### Sections (markdown content)
| # | File | Status |
|---|------|--------|
| 01 | historical-evolution.md | Complete |
| 02 | bitcoin-deep-dive.md | Complete |
| 03 | ethereum-smart-contracts.md | Not started |
| 04 | blockchain-economics.md | Not started |
| 05 | platform-comparison.md | Not started |
| 06 | privacy-technologies.md | Not started |
| 07 | stablecoins.md | Not started |
| 08 | dao-governance.md | Not started |
| 09 | sustainability.md | Not started |

### Notebooks (computational)
| # | File | Status |
|---|------|--------|
| 01 | cryptographic-primitives.ipynb | Complete |
| 02 | bitcoin-blockchain-analysis.ipynb | Not started |
| 03 | smart-contracts.ipynb | Not started |
| 04 | defi-protocols.ipynb | Not started |
| 05 | market-analysis.ipynb | Not started |
| 06 | mining-economics.ipynb | Not started |
| 07 | valuation-models.ipynb | Not started |
| 08 | privacy-forensics.ipynb | Not started |
| 09 | cryptoeconomic-modeling.ipynb | Not started |
| 10 | tokenomics.ipynb | Not started |
| 11 | consensus-simulations.ipynb | Not started |
| 12 | multichain-analysis.ipynb | Not started |
| 13 | energy-sustainability.ipynb | Not started |
