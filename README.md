# ⚙️ DAG — Computational FEM & Optimization Environment

A DAG-based computational environment for finite element simulations, workflow orchestration, and automated hyperparameter optimization.

---

## ⚡ Live Demo — Link DAG Pipeline + FEM Optimization

![Link Demo](docs/demo.gif)

This animation is generated from:

👉 `notebooks/poutre.ipynb`

It demonstrates the execution of a full computational pipeline using **Link**, a JupyterLab extension that transforms notebook cells into DAG-based workflows.

It includes:
- FEM simulation pipeline execution
- Automated mesh convergence study
- Hyperparameter optimization (nx, ny, nz)
- Execution tracking and caching system

> This workflow replaces manual convergence studies with automated optimization driven by the Link DAG system.
---

## 🚀 Quick Start

Pull and run the environment:

```bash
docker pull elmamza/fenics-link
docker run -p 8888:8888 elmamza/fenics-link
```

Then open:

```
http://localhost:8888
```

---

## 🧠 Overview

DAG provides a unified environment for scientific computing workflows based on a directed acyclic graph execution model.

It is designed to simplify the construction of complex numerical pipelines involving simulation, analysis, and optimization.

---

## 🔬 Core Capabilities

* Finite element simulations (2D / 3D)
* DAG-based workflow execution in JupyterLab
* Hyperparameter optimization pipelines
* Execution caching for efficient recomputation
* Interactive scientific computing environment
* Reproducible numerical experiments

---

## 📊 Example Workflows

A typical workflow consists of:

1. Define simulation parameters
2. Run FEM simulation
3. Compute objective function
4. Evaluate results
5. Optimize parameters iteratively

---

## 🧪 Typical Use Cases

* Computational mechanics research
* Finite element analysis (FEniCSx workflows)
* Numerical optimization experiments
* Teaching FEM concepts interactively

---

## 📦 Environment

The environment includes:

* Python scientific stack
* FEniCS / FEM solver backend
* Visualization libraries
* JupyterLab interface
* Optimization framework support

---

## 📌 Notes

* Designed for reproducible computational workflows
* Runs entirely in containerized environment
* No local installation required

---

## 🤝 Philosophy

DAG aims to unify simulation and optimization workflows into a single structured, reproducible computational environment.

---
