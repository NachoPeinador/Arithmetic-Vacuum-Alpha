# Infrared Limit of the Fine-Structure Constant
> **Global Gauge Group Center and Non-Perturbative Spectral Action**

<p align="center">
  <img src="Algebraic_Naturalness.png" alt="Algebraic Naturalness Plot" width="850">
</p>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Lean 4 Verified](https://img.shields.io/badge/Lean_4-Verified-purple.svg)](https://github.com/NachoPeinador/Arithmetic-Vacuum-Alpha/blob/main/Notebooks/alpha_Formal_Verification_of_MST_Constants_in_Lean_4.ipynb)
[![Precision](https://img.shields.io/badge/precision-1.5%20%C3%97%2010%E2%81%BB%C2%B9%E2%81%B4-brightgreen)](https://physics.nist.gov/cuu/Constants/)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0008--1822--3452-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0009-0008-1822-3452) 
[![CODATA 2022](https://img.shields.io/badge/CODATA-Converged-success)](https://physics.nist.gov/cuu/Constants/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18611629.svg)](https://doi.org/10.5281/zenodo.18611629)
[![Paper](https://img.shields.io/badge/Paper-Read_PDF-B31B1B?style=flat&logo=latex&logoColor=white)](https://github.com/NachoPeinador/Arithmetic-Vacuum-Alpha/blob/main/Paper/IR_Limit_of_alpha.pdf)
[![Open Validation Suite](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NachoPeinador/Arithmetic-Vacuum-Alpha/blob/main/Notebooks/Validation_Suite_MST_QED.ipynb)

This repository hosts the official open-source computational laboratory, high-precision evaluation engines, and mechanized formal verification suites for the mathematical physics paper **"Infrared Limit of the Fine-Structure Constant: Global Gauge Group Center and Non-Perturbative Spectral Action"**.

We present a parameter-free, analytical closed-form derivation for the electromagnetic coupling constant ($\alpha^{-1}$) at the non-perturbative infrared (IR) limit. By injecting the universal vacuum informational impedance $R_{\text{fund}}$ —derived from the Standard Model $\mathbb{Z}_6$ global gauge symmetry quotient and holographic Cantor string dynamics—into a topological phase-space expansion, our master equation matches the experimental CODATA 2022 baseline within an absolute residual discrepancy of just **1.5 × 10⁻¹⁴**.

This environment allows peer reviewers, physicists, and independent researchers to fully replicate, compile, and audit the framework's mathematical parsimony, algorithmic naturalness, and strict topological rigidity.

---

## 📄 Abstract

The fine-structure constant, $\alpha$, acts as the foundational coupling parameter governing quantum electrodynamics (QED). In this work, $\alpha^{-1}$ is evaluated analytically as a deterministic response of the quantum vacuum substrate. Rather than utilizing empirical data-fitting, this framework injects the universal vacuum informational impedance $R_{\text{fund}} = \ln 2 / (6 \ln 3)$ —derived from the Standard Model $\mathbb{Z}_6$ global gauge symmetry and holographic Cantor string dynamics—into a topological phase-space expansion. 

The master equation structures $\alpha^{-1}$ by modulating a bare 3+1 dimensional geometric manifold ($4\pi^3 + \pi^2 + \pi$) with holographic entanglement partitions ($1/4$) and topological torsional scattering cross-sections ($1 + 1/4\pi$). The resulting closed-form formulation converges with the CODATA 2022 recommended value, yielding a predictive theoretical convergence within **1.5 × 10⁻¹⁴** of the empirical baseline. By executing a topologically constrained Monte Carlo simulation to address the Look-Elsewhere Effect, we demonstrate an absolute suppression of alternative states ($p_{\text{constrained}} = 0.0$), providing strong statistical evidence for the uniqueness of the expansion. 

Furthermore, a boundary check utilizing the PSLQ integer relation algorithm reveals that further numerical refinements are restricted by current empirical truncation thresholds, establishing that the predictive closure of the master equation depends strictly on rigid topological invariants. To ensure absolute mathematical integrity, the framework's core topological identities and its structural isomorphism to the Callan-Symanzik Renormalization Group (RG) flow have been strictly certified utilizing the Lean 4 interactive theorem prover. This application solidifies the effective predictive capacity of the Modular Substrate Theory at the infrared (IR) electrodynamic limit without relying on empirical free parameters.

### The Master Equation

$$\Large \alpha^{-1} = (4\pi^3 + \pi^2 + \pi) - \frac{R_{\text{fund}}^3}{4} - \left(1 + \frac{1}{4\pi}\right)R_{\text{fund}}^5$$

> Where the core transcendental invariant **$R_{\text{fund}} = \frac{\ln 2}{6 \ln 3}$** defines the irreducible entropic cost of projecting trivalent bulk spin-network volume nodes onto a binary holographic horizon under the true Standard Model global gauge group quotient $G_{\text{SM}} = (SU(3)_C \times SU(2)_L \times U(1)_Y) / \mathbb{Z}_6$.

### Non-Perturbative Expansion Breakdown

* **$4\pi^3 + \pi^2 + \pi$ (Order 0: Bare Geometric Manifold):** Grounded in the Seeley-DeWitt heat-kernel asymptotic expansion of the spectral action in Noncommutative Geometry, the bare inverse coupling is defined as the exact sum of the unbroken isometric vacuum volumes. Derived via the compact Lie group Macdonald formula, it accounts for the electroweak bosons $SU(2) \times U(1)$ ($4\pi^3$), local Lorentz spatial rotations $SO(3) \cong \mathbb{R}P^3$ ($\pi^2$), and the discrete $\mathbb{Z}_6$ projective fiber $\mathbb{R}P^1 \cong S^1/\mathbb{Z}_2$ ($\pi$), where the antipodal involution naturally halves the unit circle metric volume. This mapping is proposed as a **Theoretical Hypothesis** whose physical integration over fractal-boundary manifolds remains an open problem.
* **$-\frac{1}{4} R_{\text{fund}}^3$ (Order 1: Holographic Phase-Space Partition):** Volumetric fractal substrate fluctuations mapped onto an enclosing information horizon, saturating the holographic entanglement bound and scaled by the universal Bekenstein-Hawking entropy coefficient of $1/4$ ($S = A / 4G_N$) and the Ryu-Takayanagi prescription.
* **$-(1 + \frac{1}{4\pi})R_{\text{fund}}^5$ (Order 2: Topological Torsion Vertex):** Secondary geometric self-interaction boundary terms native to chiral spectral actions with boundary. The factor $1$ isolates the invariant Euler characteristic ($\chi = 1$) of the fundamental interaction vertex at the boundary, while $1/4\pi$ represents the standard solid-angle normalization onto a 3D spherical boundary surface.

---

## 🎲 Algorithmic Rigor & The Look-Elsewhere Effect (LEE)

To systematically separate our framework from ad-hoc numerology or accidental data-mining alignments, this laboratory environment executes three distinct validation protocols:

### 1. Topologically Constrained Monte Carlo Simulation
* **Unconstrained Grammar ($p \approx 1.0$):** When running an open combinatorial search utilizing arbitrary transcendental variables, landing near a specific physical constant is statistically guaranteed if the search space is dense enough. This confirms the validity of the Look-Elsewhere critique.
* **Topologically Bounded Grammar ($p_{\text{constrained}} = 0.0$):** When the generative tree structure is strictly bounded to the physical and topological invariants native to a 4D Riemannian spin manifold with boundary and a $\mathbb{Z}_6$ internal space, **not a single alternative formula** converges to the experimental baseline. The master equation is shown to be a unique, singular topological intersection forced by the vacuum geometry.

### 2. Kolmogorov Complexity Minimization
By tracking the Abstract Syntax Tree (AST) node counts, we evaluate the Algebraic Naturalness Metric ($\mathcal{N}$):

$$\mathcal{N} = \frac{-\log_{10} \left( \text{Relative Error} \right)}{K(\text{AST}_{\text{Equation}})}$$

The proposed Master Equation acts as a sharp global minimum on this complexity landscape (as shown in the top chart), yielding optimal informational parsimony.

### 3. Dynamic Callan-Symanzik Inversion (SciPy)
Using high-precision numerical root-finding, we invert the standard QED 1-loop running coupling to map the effective vacuum impedance $R_{\text{eff}}(\mu)$ as a function of energy scale. This confirms that $R_{\text{fund}}$ scales dynamically as the exact topological analog of the QFT momentum cutoff, tracing a trajectory isomorphic to the Callan-Symanzik beta function.

---

## 🏆 Non-Perturbative Stability & Truncation Boundaries

The entire series is evaluated under a 100-digit arbitrary precision environment (`mpmath`) to completely eliminate floating-point truncation artifacts.

| Spectral Action Layer | Physical Description | Exact Numerical Contribution |
| :--- | :--- | :--- |
| **Order 0** | Bare Geometric Isometry Volumetrics | `137.03630377587843255920239...` |
| **Order 1** | Holographic Screening Horizon | `-0.000290689458537120378684...` |
| **Order 2** | Topological Torsion Boundary Term | `-0.000013880419880364277205...` |
| **Total Predicted** | **MST Analytical Evaluation ($\alpha^{-1}$)** | **`137.035999206000015074546...`** |
| *Experimental* | *CODATA 2022 Recommended Baseline* | *`137.035999206`* |
| *Deviation* | *Absolute Residual Discrepancy* | **`1.507454650502140e-14`** |

* **Asymptotic PSLQ Bound Check:** Running the Integer Relation Algorithm (PSLQ) at 150-digit precision to isolate a closed-form transcendental match for the next analytical pole ($c_3 R_{\text{fund}}^7$) returns a verified *Null* or *None* result. This confirms that the residual cannot be data-mined from contemporary baselines due to the physical truncation of current experimental measurements, proving further refinement requires a pure non-perturbative field theoretic calculation over the fractal substrate's generalized Dixmier trace.
* **Potential Well Steepness:** Subjecting the structural coefficients to a micro-perturbation ($\epsilon = 10^{-6}$) shifts the equation from its stable topological manifold, collapsing the precision output immediately by **over four orders of magnitude ($>10^4\times$)**. The model strictly rejects flat, flexible parameter landscapes.

---

## 💻 Formal Verification in Lean 4

To ensure absolute mathematical integrity, we bypass numerical evaluation entirely and prove the core structural pillars of our framework within the **Lean 4** interactive theorem prover. The compiled script `MST_Foundations_Complete.lean` certifies:
1. **Theorem 1 (Impedance Equivalence):** Proves that the holographic entropy ratio $\frac{\ln 2}{6\ln 3}$ and the discrete fractional state $\frac{1/6}{\log_2 3}$ are algebraically identical (Certified exact, 0 *sorries*).
2. **Theorem 2 (Macdonald Volumes Sum):** Certifies that the bi-invariant Lie group metric volumes of the unbroken vacuum isometries sum exactly to $4\pi^3 + \pi^2 + \pi$ (Certified exact, 0 *sorries*).
3. **Theorem 3 (Topological Beta Function):** Mechanizes the differential chain rule of our non-commutative master equation, proving its structural isomorphism to the Callan-Symanzik beta function.

---

## 🛠️ Scientific Reproducibility & Auditing

The full computational pipeline is cross-linked and executable natively on cloud architectures.

| Research Domain | Computational Suite | Core Verifications & Mappings |
| :--- | :--- | :--- |
| **⚛️ Electrodynamic Invariants** | [![Open Validation Suite](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NachoPeinador/Arithmetic-Vacuum-Alpha/blob/main/Notebooks/Validation_Suite_MST_QED.ipynb) | • 100-digit precision calculation.<br>• Constrained Monte Carlo LEE simulation.<br>• PSLQ boundary truncation test.<br>• Callan-Symanzik RG SciPy mapping. |
| **⚙️ Formal Mathematics** | [![Open Lean 4 Workspace](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NachoPeinador/Arithmetic-Vacuum-Alpha/blob/main/Notebooks/alpha_Formal_Verification_of_MST_Constants_in_Lean_4.ipynb) | • Automated installation of Lean 4 / Mathlib.<br>• Exact proof of Theorems 1 and 2 (0 *sorries*).<br>• Chain-rule verification of the topological beta function. |

### Execution Instructions
1. **Click** either of the "Open in Colab" badges above to load the validated environments.
2. **Run All:** Navigate to the top options menu and select `Runtime` > `Run all` (or trigger `Ctrl + F9`).
3. **Audit:** The scripts automatically compile the proofs in Lean 4, or compute the high-precision metrics, run the stochastic loop mining, and output the Naturalness complexity plot in Python.

---

## 📂 Repository Architecture

```text
├── README.md                           # Extended overview & statistical review
├── LICENSE                             # MIT Open-Source licensing definitions
├── Algebraic_Naturalness.png           # Complexity vs Precision Plot
├── Notebooks/
│   ├── Validation_Suite_MST_QED.ipynb  # Interactive Multi-Stage Validation Suite
│   └── alpha_Formal_Verification_of_MST_Constants_in_Lean_4.ipynb # Lean 4 Proof Suite
└── Paper/
    ├── IR_Limit_of_alpha.pdf             # Main peer-review manuscript
    └── IR_Limit_of_alpha.tex             # Complete LaTeX source code

```

---

## 📚 Citation

If you implement this topological phase-space expansion, the algebraic naturalness metric, or the master validation engine in your research, please cite our current submission and its foundational companion material:

```bibtex
@article{peinador2026infrared,
  title={Infrared Limit of the Fine-Structure Constant: Global Gauge Group Center and Non-Perturbative Spectral Action},
  author={Peinador Sala, Jos{\'e} Ignacio},
  journal={International Journal of Theoretical Physics},
  year={2026},
  volume={Submitted},
  url={[https://github.com/NachoPeinador/Arithmetic-Vacuum-Alpha](https://github.com/NachoPeinador/Arithmetic-Vacuum-Alpha)},
  doi={10.5281/zenodo.18611629}
}

@article{peinador2026foundational,
  title={Information-Theoretic Impedance from Discrete Gauge Symmetries and Cantor-Set Holography},
  author={Peinador Sala, Jos{\'e} Ignacio},
  journal={Zenodo},
  year={2026},
  doi={10.5281/zenodo.20546608},
  note={Companion Foundational Material}
}

```

---

## 🛡️ Licensing

* The computational simulation source code is licensed under the permissive **MIT License**—see the [LICENSE](https://opensource.org/licenses/MIT) file.
* The scientific manuscript text and core theoretical frameworks are protected under the **CC BY 4.0 International License**.

## ✉️ Contact

**José Ignacio Peinador Sala** — *Independent Researcher, Valladolid, Spain* 📧 [joseignacio.peinador@gmail.com](https://www.google.com/search?q=mailto%3Ajoseignacio.peinador%40gmail.com) | ORCID: [0009-0008-1822-3452](https://orcid.org/0009-0008-1822-3452)

---

## 🔭 Philosophical Context

> *"I do not know what I may appear to the world, but to myself I seem to have been only like a boy playing on the sea-shore... whilst the great ocean of truth lay all undiscovered before me."* — **Isaac Newton**

The determination of the fine-structure constant ($\alpha$) is one of the greatest challenges in the history of theoretical physics. For almost a century, brilliant minds have sought the origin of this number, building a gigantic puzzle of knowledge where every discovery, every theory, and every experiment has served to narrow down the mystery.

This work is born from the humility of knowing oneself to be part of that shared effort. We do not claim to have solved the enigma in its entirety, but simply to have contributed one more piece: one that, by observing the vacuum through the lens of $\mathbb{Z}_6$ modular topology and informational impedance, seems to fit with astonishing parsimony and precision. If our master equation manages to approximate the value measured by CODATA so closely, it is thanks to the path paved by all those who, day after day, face the unknown in laboratories and offices around the world.

We recognize and honor the work of the global scientific community. Science is not a sprint, but a cathedral built stone by stone. This analytical framework, forged from independent research, is merely our attempt to place one of those stones with rigor and honesty, hoping it will help others to continue exploring the vast ocean of truth that still surrounds us.

> *"The architecture of the universe is one, and the human effort to understand it is a path we all walk together, step by step."*

---

**Last Update:** July 2026 | **Status:** Submitted to *International Journal of Theoretical Physics (IJTP)* | Built with ⚙️, \LaTeX, & 🐍

---

> 🌌 **El Universo Aritmético / The Arithmetic Universe**
> 🇬🇧 *This research is part of the theoretical framework of **The Arithmetic Universe**, the theory which postulates that fundamental reality is not hidden in infinite chaos, but in the elegant and humble architecture of integers.*
> 🔗 **[Discover the central repository, the interactive notebooks, and the Lean 4 validation here](https://github.com/NachoPeinador/EL_UNIVERSO_ARITMETICO)**.
> 🇪🇸 *Esta investigación forma parte del marco teórico de **El Universo Aritmético**, la teoría que postula que la realidad fundamental no se esconde en el caos infinito, sino en la elegante y humilde arquitectura de los números enteros.*
> 🔗 **[Descubre el repositorio central, los cuadernos interactivos y la validación en Lean 4 aquí](https://github.com/NachoPeinador/EL_UNIVERSO_ARITMETICO)**.

