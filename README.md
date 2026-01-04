# AIΩN Foundations — Paper V

## WARP Graphs: Emergent Dynamics from Deterministic Rewrite Systems

|  |  |  |
|--|--|--|
| **DOI** | `10.5281/zenodo.18146884` | [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18146884.svg)](https://doi.org/10.5281/zenodo.18146884) |

### Front Matter

WARP Graphs: Emergent Dynamics from Deterministic Rewrite Systems  
James Ross (ORCID: [0009-0006-0025-7801](https://orcid.org/0009-0006-0025-7801))  
Independent Researcher  
AIΩN Foundations Series — Paper V  
January 2026  

---

## Overview

This repository contains the LaTeX source and compiled PDF for Paper V of the AIΩN Foundations Series.

Paper V introduces the dynamical principle of the AIΩN framework, completing the transition from kinematics to dynamics. It equips deterministic rewrite systems with a local action functional and complex amplitude measure, deriving quantum-like interference, unitarity, and Schrödinger-type evolution as emergent phenomena under observer-induced projection. The paper proves that unitarity arises from local reversibility, action antisymmetry, and branch conservation, and establishes a continuum approximation yielding a Quantum Cellular Automaton interpretation.

---

## Contents

- `paper/main.tex` — Primary LaTeX manuscript (Paper V)
- `paper/aion.cls` — AIΩN Foundations class file
- `paper/macros.tex` — Notation and helper macros
- `paper/diagrams.tex` — TikZ diagrams and global styles
- `paper/refs.bib` — Bibliography
- `Makefile` — Convenience build (latexmk + jobname/output directory)
- `pdf/` — Compiled PDF + LaTeX build artifacts

---

## Build Instructions

Requires:
- TeX Live or MiKTeX
- `latexmk` recommended (used by the Makefile)

Build from the repo root with:

```bash
make
```

Clean + rebuild:

```bash
make clean
make
```

The compiled paper appears in `./pdf/` as `aion-paper-05-dynamics.pdf`.

---

## AIΩN Foundations Series

This paper is part of a six-paper foundational series:

1. [WARP Graphs: A Worldline Algebra for Recursive Provenance](https://github.com/flyingrobots/aion-paper-01-warp)
2. [WARP Graphs: Canonical State Evolution and Deterministic Worldlines](https://github.com/flyingrobots/aion-paper-02-worldlines)
3. [WARP Graphs: Computational Holography & Provenance Payloads](https://github.com/flyingrobots/aion-paper-03-holography)
4. [WARP Graphs: Rulial Distance & Observer Geometry](https://github.com/flyingrobots/aion-paper-04-observer-geometry)
5. **WARP Graphs: Emergent Dynamics from Deterministic Rewrite Systems *(this repo)***
6. WARP Graphs: Ethics of Deterministic Replay & Provenance Sovereignty
7. The AIΩN Computer: Architecture & OS (JITOS)

---

## License

This repository contains the Paper V manuscript, figures, compiled PDF, and documentation. These materials are © 2026 James Ross and licensed under **Creative Commons Attribution 4.0 (CC BY 4.0)**; see `LICENSE` for details.

The AIΩN Runtime and associated software projects referenced by the paper are *not* part of this repository; they live in separate repositories under their own licenses.

---

## More on AIΩN

For updates, see the main AIΩN repository:
[github.com/flyingrobots/aion](https://github.com/flyingrobots/aion)
