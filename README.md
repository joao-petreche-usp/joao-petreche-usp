# Hi, I'm João Roberto Diego Petreche 👋

**Professor & Researcher** · Escola Politécnica da USP (POLI) · Department of Construction Engineering (PCC)

Naval and Oceanic Engineer with a Ph.D. from the University of São Paulo (USP). My research integrates rigorous engineering design principles with high-performance building energy simulation (BEM), combining computational methods and AI to accelerate performance-based design.

📄 **Academic profile:** [Lattes CNPq](http://lattes.cnpq.br/4372288782582811)

---

## 🔬 Research & Curriculum: A Connected Vision

My work operates on two interconnected fronts:

**1. Applied Research** — Developing a novel computational framework for multi-objective building optimization, using Axiomatic Design, Google OR-Tools (CP-SAT), and the EnergyPlus Python API. This research generates real, complex engineering problems that demand cutting-edge AI and cloud computing solutions.

**2. AI Engineering Curriculum** — The hands-on experience gained from this research directly feeds the [`AI-Engineering-Curriculum`](https://github.com/joao-petreche-usp/AI-Engineering-Curriculum) repository, which documents methods, tools, and workflows at the intersection of Scientific AI Engineering and high-performance computing.

> The research *is* the curriculum. Real problems, real infrastructure, real methods.

---

## 🚀 Featured Research Project

### Hierarchical & Sequential Multi-Objective Building Optimization

> *Hierarchical and Sequential Multi-Objective Optimization of Buildings: Implementing Axiomatic Design via Google OR-Tools and EnergyPlus Python API*

This project addresses a fundamental challenge in sustainable architecture: the prohibitively expensive computational cost of performance-based building design.

**Core methodology:**

- **Axiomatic Design (AD)** — Systematic decoupling of design parameters from functional requirements using a triangular matrix structure, replacing traditional "black-box" evolutionary algorithms
- **Google OR-Tools (CP-SAT)** — Mathematically guaranteed lexicographic multi-objective optimization with native support for discrete variables directly from commercial catalogs
- **EnergyPlus Python API** — High-fidelity thermal and energy simulation integrated programmatically into the optimization loop

**Target impact:** Reduce the computational cost of complex building energy simulations by over 90% while ensuring identification of true Pareto-optimal solutions.

**Current status:** Public reproducibility companion released — [`EnergyPlus-API-Colab`](https://github.com/joao-petreche-usp/EnergyPlus-API-Colab). The canonical GCP VM pipeline reproduces the published Pareto front; GSA Morris over 5 design parameters (90 simulations) ranks `orientation`, `wall_r`, and `roof_r` as the Level-1/2 axiomatic priorities, validated against a 192-simulation exhaustive ground truth on the `5ZoneAirCooled` archetype.

> 📌 **For Google Cloud Research Credits reviewers:** The Proof of Concept is complete and publicly reproducible at [`EnergyPlus-API-Colab`](https://github.com/joao-petreche-usp/EnergyPlus-API-Colab) — the May 2026 refactor scopes the repo as the paper companion and ships the full GSA → CP-SAT lexicographic → EnergyPlus pipeline with a validated 3-candidate MLT Pareto front. Requested credits (**USD 4,168.52** — N4 Compute Engine + Codey + GCS) fund the scale-out from this single-archetype validation to DOE reference multi-zone commercial models, where the 91.2% function-evaluation reduction (Talami et al. 2024) translates directly into weeks→hours of wall-clock savings. Full proposal: [Pitch Deck](https://docs.google.com/presentation/d/1mwtuoV0NTyVYyLAwFpMRV4MSvGqNZ3tGkKQTn-5whL4/edit?usp=drive_link) · [Executive Report](https://docs.google.com/document/d/1Ntieeq1uP-dpc0YyAWM94hxU7kfFrBKzq0iXK6UCdcM/edit?usp=sharing).

---

## 📂 Public Repositories

| Repository | Description |
|---|---|
| [`EnergyPlus-API-Colab`](https://github.com/joao-petreche-usp/EnergyPlus-API-Colab) | Paper-reproducibility companion — hierarchical multi-objective building optimization via Axiomatic Design, OR-Tools and EnergyPlus Python API |
| [`AI-Engineering-Curriculum`](https://github.com/joao-petreche-usp/AI-Engineering-Curriculum) | Methods, tools, and workflows in Scientific AI Engineering — built from real research experience |

---

## 🛠️ Tech Stack

**Simulation & Optimization**
`EnergyPlus` `Google OR-Tools (CP-SAT)` `Python`

**Infrastructure & Compute**
`Google Cloud (Compute Engine · GCS)` `Google Colab` `Cloud Shell`

**Development**
`VS Code` `GitHub` `DVC`

**Research & Literature**
`SciSpace` `NotebookLM` `Scite.ai` `Zotero`

---

## 🎓 Background

- **Ph.D.** — University of São Paulo (USP)
- **Naval and Oceanic Engineering** — Escola Politécnica da USP (POLI)
- **Department** — Construction Engineering (PCC / POLI-USP)
- **Focus areas** — Building Energy Modeling (BEM) · Axiomatic Design · Multi-Objective Optimization · Scientific AI Engineering

---

## 📫 Contact & Academic Profile

- 📄 [Lattes CNPq](http://lattes.cnpq.br/4372288782582811)
- 🏛️ [Escola Politécnica da USP](https://www.poli.usp.br/) — [Department of Construction Engineering (PCC)](https://www.poli.usp.br/departamentos/pcc-engenharia-de-construcao-civil/)

---

*Sharing research projects on energy simulation, engineering design, and AI applied to the built environment.*
