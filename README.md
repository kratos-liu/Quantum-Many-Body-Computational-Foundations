# Academic Research & Computational Physics Base

This repository is the public portfolio companion for my resume section:
**Scientific Computing Architecture and Low-Level Algorithm Research
(Ph.D. core work)**.

## Overview

My core research and engineering experience focuses on numerically exact
algorithms for strongly correlated electron systems, especially Determinant
Quantum Monte Carlo (DQMC). The work includes Hamiltonian construction,
Green's-function updates, observable measurement, data-analysis pipelines, and
symmetry-based analysis of the Monte Carlo sign problem.

I have independently developed large-scale scientific simulation workflows and
run multi-day DQMC jobs in MPI environments with roughly 560 CPU cores.

## Public Scope

The first two projects are under review at Physical Review B. This repository
keeps the descriptions at resume level and omits unpublished manuscript details
or private implementation files.

---

## 1. Large-Scale DQMC Engine and Multi-Probe Measurements for a Fermion-Ising Coupled Model

**Status:** Under Review at Physical Review B

**Computational focus:** Build a dedicated DQMC simulation engine for a
fermion-Ising coupled model and scan the finite-temperature phase diagram near
a quantum critical point.

**Resume-aligned contributions:**

- Independently implemented the model-specific DQMC simulation engine.
- Produced core observables for phase-boundary identification.
- Built an analysis pipeline from raw DQMC measurements to SAC spectra,
  imaginary-time Green's-function crossing checks, and phase-boundary analysis.
- Kept error estimation and cross-validation steps in the data workflow.

<img width="500" alt="Fig1_Cart" src="https://github.com/user-attachments/assets/c9d8e7f8-7018-4e7d-9aaf-8f0f1edb848a" />

---

## 2. Symmetry Analysis for the Monte Carlo Sign Problem

**Status:** Under Review at Physical Review B

**Computational focus:** Analyze how spatially anisotropic band structures can
worsen the Monte Carlo sign problem, starting from the structure of fermion
propagator matrices.

**Resume-aligned contributions:**

- Analyzed algebraic conditions under which specific symmetry configurations
  lead to non-negative fermionic weights.
- Combined a partial particle-hole transformation with spatial mirror symmetry
  to refactor the fermion propagator matrix.
- Proved that, under mirror-symmetric configurations, the spin-up and spin-down
  determinants satisfy a similarity-transform relation.
- Used the derivation to explain a major mechanism behind low-temperature sign
  deterioration and to provide theoretical guidance for extending the
  accessible sampling-temperature window.

<img width="500" alt="Fig1_schematic" src="https://github.com/user-attachments/assets/ed8e44bc-3066-4343-ba47-91f95ee6d478" />

---

## 3. DQMC Engine Optimization and Observables for the Two-Dimensional Hubbard Model

**Status:** Published in Physical Review A

**Computational focus:** Refactor and verify a DQMC workflow for a two-dimensional
Hubbard model with next-nearest-neighbor and third-nearest-neighbor hopping.

**Resume-aligned contributions:**

- Reconstructed the DQMC computation workflow for the extended two-dimensional
  Hubbard model.
- Verified implementation correctness through benchmark cases and consistency
  checks across physical observables.
- Derived and implemented key observables, including vertex corrections to the
  pairing susceptibility.
- Supported numerical analysis of spin-triplet superconducting instability.

**Publication:** Physical Review A, DOI:
[10.1103/9552-rz3h](https://doi.org/10.1103/9552-rz3h)
