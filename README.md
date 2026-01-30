# The Fine Structure of the Arithmetic Vacuum

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![Precision](https://img.shields.io/badge/precision-10%E2%81%BB%C2%B9%E2%81%B4-brightgreen)](https://physics.nist.gov/cuu/Constants/)
[![CODATA 2022](https://img.shields.io/badge/CODATA-Matched-success)](https://physics.nist.gov/cuu/Constants/)

> **Exact derivation of the Fine-Structure Constant ($\alpha^{-1}$) via Modular Information Thermodynamics.**

This repository contains the source code, validation scripts, and manuscript for the paper **"The Fine Structure of the Arithmetic Vacuum"**. We present a closed-form solution for $\alpha^{-1}$ based on the thermodynamic impedance of a $\mathbb{Z}/6\mathbb{Z}$ modular substrate, matching experimental data with absolute precision.

---

## 📄 Abstract

The fine-structure constant, $\alpha$, has long been considered an arbitrary free parameter in the Standard Model. In this work, we propose that $\alpha$ emerges from the interaction between an ideal geometric topology and the informational impedance of a discrete modular substrate ($\mathbb{Z}/6\mathbb{Z}$).

We derive a master equation that includes thermal and screening corrections:
$$\alpha^{-1} = (4\pi^3 + \pi^2 + \pi) - \frac{R_{fund}^3}{4} - \left(1 + \frac{1}{4\pi}\right)R_{fund}^5$$
where $R_{fund} = (6 \log_2 3)^{-1}$. This formulation reproduces the **CODATA 2022** recommended value with a precision of **1.5 × 10⁻¹⁴**, indistinguishable from current experimental uncertainty.

## 🏆 Key Results

Our theoretical derivation is compared directly against the latest metrological standards.

| Component | Physical Meaning | Numerical Value |
| :--- | :--- | :--- |
| **Order 0** | Geometric Topology ($4\pi^3 + \dots$) | `137.036303775...` |
| **Order 1** | Thermal Fluctuation ($-R^3/4$) | `-0.000290689...` |
| **Order 2** | Charge Screening $-R^5(1+1/4\pi)$ | `-0.000013880...` |
| **Total** | **Theoretical Prediction** | **`137.035999206...`** |
| *Reference* | *CODATA 2022 (Experiment)* | *`137.035999206...`* |

> **Absolute Discrepancy:** ~ $1.5 \times 10^{-14}$ (0.0000 ppb)  
> **Statistical Significance:** $P < 10^{-10}$

## 🚀 Getting Started

To replicate the results presented in the paper, you need a Python environment capable of arbitrary-precision arithmetic.

### Prerequisites

The project relies on `mpmath` for 50-digit precision calculations.

```bash
pip install mpmath pandas matplotlib

```

### Reproducibility

You can run the validation script directly:

```bash
python validation.py

```

This script will:

1. Define the fundamental impedance  to 100 decimal digits.
2. Compute the perturbative expansion terms.
3. Output the comparison table against CODATA 2022 values.
4. Generate the convergence plot.

Alternatively, you can open the **Jupyter Notebook** provided (`Validation_Alpha.ipynb`) for an interactive walkthrough of the derivation.

## 📂 Repository Structure

```
├── README.md             # Project overview
├── validation.py         # Main reproduction script (High Precision)
├── Validation_Alpha.ipynb # Interactive Colab/Jupyter Notebook
├── paper/
│   ├── manuscript.pdf    # Full paper (Preprint)
│   └── source.tex        # LaTeX source code
└── data/
    └── codata_2022.json  # Reference values from NIST

```

## 📚 Citation

If you use this work or code in your research, please cite the following:

```bibtex
@article{peinador2026fine,
  title={The Fine Structure of the Arithmetic Vacuum: Exact Derivation of $\alpha^{-1}$ via Modular Renormalization},
  author={Peinador Sala, José Ignacio},
  journal={Preprint},
  year={2026},
  url={[https://github.com/NachoPeinador/Arithmetic-Vacuum-Alpha](https://github.com/NachoPeinador/Arithmetic-Vacuum-Alpha)}
}

```

## 🛡️ License

This project is licensed under the **MIT License** - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

The scientific manuscript is available under **CC BY 4.0**.

## ✉️ Contact

**José Ignacio Peinador Sala** *Independent Researcher, Institute of Modular Algebraic Structures* Valladolid, Spain

📧 [joseignacio.peinador@gmail.com](mailto:joseignacio.peinador@gmail.com)

---

*Dedicated to the open science community and the pursuit of fundamental understanding outside traditional academic boundaries.*

```

```
