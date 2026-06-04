# Hi, I'm João Roberto Diego Petreche 👋

**Professor & Researcher** · Escola Politécnica da USP (POLI) · Department of Construction Engineering (PCC)

Naval and Oceanic Engineer with a Ph.D. from the University of São Paulo (USP). My research integrates rigorous engineering design principles with high-performance building energy simulation (BEM), combining computational methods and AI to accelerate performance-based design.

📄 **Academic profile:** [Lattes CNPq](http://lattes.cnpq.br/4372288782582811)

---

## 🔬 Research & Curriculum: A Connected Vision

My work operates on two interconnected fronts:

**1. Applied Research** — Developing a novel computational framework for multi-objective building optimization, using Axiomatic Design, global sensitivity analysis (Sobol), and the EnergyPlus Python API. This research generates real, complex engineering problems that demand cutting-edge AI and cloud computing solutions.

**2. AI Engineering Curriculum** — The hands-on experience gained from this research directly feeds the [`AI-Engineering-Curriculum`](https://github.com/joao-petreche-usp/AI-Engineering-Curriculum) repository, which documents methods, tools, and workflows at the intersection of Scientific AI Engineering and high-performance computing.

> The research *is* the curriculum. Real problems, real infrastructure, real methods.

---

## 🚀 Featured Research Project

### Sequential Block-Propagation for Building Energy Optimization

> *Decoupling Building Energy Models for Lexicographic Multi-Objective Optimization: A Global Sensitivity-Guided Sequential Block-Propagation Framework* (Petreche & Correa, under review at *Energy and Buildings*).

This project addresses a fundamental challenge in sustainable architecture: the prohibitively expensive computational cost of performance-based building design, where each candidate evaluation requires a detailed annual EnergyPlus simulation.

**Core methodology:**

- **Sobol-Saltelli global sensitivity analysis** — Variance decomposition over the four-parameter design space (`N = 128`, 768 EnergyPlus simulations) quantifies how each design parameter drives the functional requirements (thermal discomfort, HVAC energy).
- **Axiomatic Design (AD)** — Systematic decoupling of design parameters from functional requirements using a variance-based design matrix `A_ij := S_T(FR_i ← DP_j)`, replacing the heuristic "engineering judgment" traditionally required to assign DPs to FRs with a computable, data-driven criterion.
- **Sequential block-propagation** — Two-block partition (comfort vs envelope) solved sequentially, with each candidate verified by an annual EnergyPlus simulation through the runtime API.

**Validated impact:** 100 % Pareto effectiveness against the exhaustive 192-simulation ground truth (HV ratio = 1.000, IGD = 0.0) at **66.7 % computational savings** (64 vs. 192 simulations) on the DOE 5ZoneAirCooled prototype in Chicago.

**Current status:** Public reproducibility companion released — [`EnergyPlus-API-Colab`](https://github.com/joao-petreche-usp/EnergyPlus-API-Colab). The canonical GCP VM pipeline reproduces the Sobol-Saltelli sensitivity decomposition and the four-point Pareto front against the validated 192-simulation exhaustive ground truth on the `5ZoneAirCooled` archetype.

---

## 📂 Public Repositories

| Repository | Description |
|---|---|
| [`EnergyPlus-API-Colab`](https://github.com/joao-petreche-usp/EnergyPlus-API-Colab) | Companion code for Petreche & Correa, *Decoupling Building Energy Models for Lexicographic Multi-Objective Optimization* (under review, *Energy and Buildings*) |
| [`AI-Engineering-Curriculum`](https://github.com/joao-petreche-usp/AI-Engineering-Curriculum) | Methods, tools, and workflows in Scientific AI Engineering — built from real research experience |

---

## 🛠️ Tech Stack

**Simulation & Optimization**
`EnergyPlus` `SALib (Sobol)` `Google OR-Tools (CP-SAT)` `Python`

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
