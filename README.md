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

## 1. Model-Specific DQMC Implementation and Multi-Probe Measurements for a Fermion-Ising Coupled Model

**Status:** Under Review at Physical Review B

**Computational focus:** Implement a model-specific DQMC simulation workflow for a
fermion-Ising coupled model and scan the finite-temperature phase diagram near
a quantum critical point.

**Resume-aligned contributions:**

- Independently implemented the model-specific DQMC simulation code.
- Produced core observables for phase-boundary identification.
- Built an analysis pipeline from raw DQMC measurements to SAC spectra,
  imaginary-time Green's-function crossing checks, and phase-boundary analysis.
- Kept error estimation and cross-validation steps in the data workflow.

<img width="500" alt="Fig1_Cart" src="https://github.com/user-attachments/assets/c9d8e7f8-7018-4e7d-9aaf-8f0f1edb848a" />

---

## 2. Symmetry Analysis for the Monte Carlo Sign Problem

**Status:** Under Review at Physical Review B

**Computational focus:** Analyze the determinant sign structure of the
spin-dependent fermion-Ising model for $\alpha < 1$, where the standard
half-filled $\alpha=1$ particle-hole positivity proof no longer applies because
the two spin sectors have different kinetic matrices.

**Resume-aligned contributions:**

- Analyzed algebraic conditions under which specific symmetry configurations
  lead to non-negative fermionic weights.
- Used a partial particle-hole transformation together with the spatial
  $x \leftrightarrow y$ mirror operation to relate the down-spin determinant to
  the up-spin determinant evaluated on the mirror-transformed Ising
  configuration.
- Showed that mirror-symmetric configurations, including checkerboard AFM
  backgrounds, yield a nonnegative square-like fermionic weight.
- Connected this sufficient condition with average-sign diagnostics to
  rationalize the favorable sign behavior observed in the sampled parameter
  window.

<img width="500" alt="Fig1_schematic" src="https://github.com/user-attachments/assets/ed8e44bc-3066-4343-ba47-91f95ee6d478" />

---

## 3. Numerically Exact DQMC Study of Spin-Triplet Pairing in a Two-Dimensional Repulsive Hubbard Model

**Status:** Published in Physical Review A

**Computational focus:** Use determinant quantum Monte Carlo to study
unconventional pairing tendencies in a spin-balanced two-dimensional repulsive
Hubbard model with next-nearest-neighbor and third-nearest-neighbor hopping,
with the filling tuned close to a type-II Van Hove singularity.

**Resume-aligned contributions:**

- Performed a numerically exact DQMC study of possible pairing channels with
  different symmetries under repulsive interactions.
- Computed pairing susceptibilities and vertex contributions to identify the
  ordering tendency of the spin-triplet $p$-wave channel.
- Found increasingly pronounced spin-triplet $p$-wave pairing signatures as
  temperature decreases and interaction strength grows from weak to
  intermediate coupling.
- Analyzed spin-spin correlations near the type-II Van Hove singularity and
  connected the dominant ferromagnetic correlations with the spin-triplet
  pairing instability.

**Publication:** Physical Review A, DOI:
[10.1103/9552-rz3h](https://doi.org/10.1103/9552-rz3h)
