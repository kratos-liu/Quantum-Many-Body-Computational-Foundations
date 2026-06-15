## ⚛️ Academic Research & Computational Physics Base

> **Overview:** My core expertise lies in the deep refactoring and performance optimization of underlying numerically exact algorithms (e.g., Determinant Quantum Monte Carlo, DQMC) for strongly correlated electron systems. I specialize in independently developing and optimizing large-scale, high-performance simulation engines, and effectively mitigating computational breakthroughs and sampling breakdown bottlenecks (such as the Sign Problem in QMC) from both mathematical and algorithmic architecture dimensions.

---

### 1. Thermodynamics and dynamics near a ferromagnetic quantum critical point
* **Status:** Under Review at Physical Review B
* **🔒 `[Note: Full manuscript is currently confidential and available upon request for interview evaluation only.]`**
* **🎯 The Computational Challenge:** Mapping a high-precision finite-temperature phase diagram near a quantum critical point and accurately extracting the dynamical signatures of non-Fermi liquid (Bad Metal) behaviors.
* **⚙️ Engineering Architecture & Pipeline:** Independently developed a large-scale, high-performance DQMC simulation engine tailored for the fermion-Ising coupling model to map the complete high-precision有限温相图. Integrated a multi-probe data analytical pipeline (including stochastic analytic continuation spectra, imaginary-time Green’s function midpoints, and self-energy crossing detection) to achieve rigorous cross-validation of computational results.
* **📊 Key Benchmark:** Not only accurately pinpointed the ferromagnetic quantum critical point at $h_c = 3.47(1)$ (with critical exponent $z\nu = 0.64(2)$), but quantitatively determined the crossover boundary from marginal Fermi-liquid (MFL) to Bad Metal through large-scale numerical simulations and multi-probe cross-validation.

<img width="500" alt="Fig1_Cart" src="https://github.com/user-attachments/assets/c9d8e7f8-7018-4e7d-9aaf-8f0f1edb848a" />

---

### 2. Mining underlying symmetry to mitigate the Monte Carlo "Sign Problem"
* **Status:** Under Review at Physical Review B
* **🔒 `[Note: Full manuscript is currently confidential and available upon request for interview evaluation only.]`**
* **🎯 The Computational Challenge:** When spin-dependent hopping anisotropy (altermagnetic band geometry, $\alpha < 1$) is introduced, the notorious "Sign Problem" causes the signal-to-noise ratio to decay exponentially at low temperatures, leading to a complete breakdown of traditional Monte Carlo sampling.
* **⚙️ Mathematical Optimization & Matrix Refactoring:** Addressed the bottleneck directly from the underlying matrix algebra. By executing a rigorous algebraic refactoring of the fermion propagator matrix—specifically combining a partial particle-hole transformation with the system's spatial mirror symmetry ($x\leftrightarrow y$)—I strictly proved mathematically that mirror-symmetric configurations (especially checkerboard antiferromagnetic backgrounds) possess a guaranteed non-negative fermionic weight.
* **📊 Key Benchmark:** Successfully mitigated the low-temperature algorithm breakdown effects via exact mathematical optimization. Extracted high-fidelity thermal critical fields and revealed the spin-resolved occupation imbalance structure in momentum space.

<img width="500" alt="Fig1_schematic" src="https://github.com/user-attachments/assets/ed8e44bc-3066-4343-ba47-91f95ee6d478" />

---

### 3. Spin-triplet pairing instability in a two-dimensional repulsive Hubbard model
* **Status:** Published in Physical Review A (DOI: [10.1103/9552-rz3h](https://doi.org/10.1103/9552-rz3h))
* **🎯 The Computational Challenge:** Numerically exact simulation of superconducting tendencies with unconventional pairing symmetries under repulsive interactions, involving complex hopping topologies (next-nearest and third-nearest neighbor).
* **⚙️ Algorithmic Implementation & Core Refactoring:** Successfully executed and refactored a numerically exact DQMC computational pipeline for systems with next-nearest and third-nearest neighbor hopping. Derived and computed explicit values for highly complex physical observables, including the vertex contribution to pairing susceptibility.
* **📊 Key Benchmark:** Provided clear numerical evidence and reliable qualitative conclusions for the spin-triplet p-wave pairing instability driven by ferromagnetic correlations near a type-II Van Hove singularity (VHS).
