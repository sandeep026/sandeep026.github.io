---
layout: page
title: Softwares
permalink: /soft/
---

My research focuses on **trajectory optimization** and **numerical methods**, developing efficient algorithms to solve complex, constrained dynamic systems. Below is an overview of the computational tools, solvers, and publishing frameworks that power my computational pipeline.

---

## Technical Stack

| Domain | Technologies & Libraries | Application in Research |
| :--- | :--- | :--- |
| **Optimization & Dynamics** | `CasADi` • `IPOPT` • `JAX` | Non-linear programming (NLP) transcription, automatic differentiation, interior-point solving, and accelerated gradient computations. |
| **Numerical Computing** | `Python` • `NumPy` • `SciPy` | Numerical integration of dynamic systems, linear algebra operations, state estimation, and custom algorithm development. |
| **Data Visualization** | `Matplotlib` • `draw.io` | Publication-ready phase plots, state/control histories, convergence curves, and system schematics. |
| **Publishing & Web** | `LaTeX` • `Markdown` • `Jekyll` | Rigorous mathematical typesetting, reproducible project notes, and static site maintenance. |

---

## Methodology & Workflows

### 1. Trajectory Optimization & Optimal Control
* **Direct Methods:** Transcribing continuous-time optimal control problems into discrete non-linear programs using **CasADi** via direct collocation and multiple shooting techniques.
* **Large-Scale Solvers:** Interfacing transcriptions with **IPOPT** to solve high-dimensional trajectory optimization problems under state and control constraints.
* **Algorithmic Differentiation:** Leveraging **JAX** for vectorized computations, fast gradient calculations, and parallelized trajectory rollouts.

### 2. Numerical Simulation & Analysis
* **Dynamic Simulation:** Building dynamic forward-simulation pipelines using **NumPy** and **SciPy** differential equation solvers for trajectory validation.
* **Performance Benchmarking:** Analyzing convergence rates, execution times, and solver robustness across initial state estimates.

### 3. Scientific Communication
* **Publication Graphics:** Generating vector graphics and high-resolution plots via **Matplotlib**, paired with structural system diagrams created in **draw.io**.
* **Typesetting & Documentation:** Deriving theoretical formulations in **LaTeX** and integrating documentation into **Jekyll** using **Markdown**.
