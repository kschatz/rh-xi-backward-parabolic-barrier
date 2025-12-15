# Riemann Hypothesis: Backward Parabolic Positivity Barriers for the Xi Flow

**DOI:** [10.5281/zenodo.17636625](https://doi.org/10.5281/zenodo.17636625)<br>
**PDF:** [Download preprint](https://zenodo.org/records/17636625/files/schatz_riemann_hypothesis_backward_parabolic_positivity_barriers_xi_flow.pdf)

## Overview

We develop a parabolic positivity method for the Riemann Xi function along the de Bruijn heat flow (the Xi flow). We construct backward Carleman-Kato barriers that propagate a positivity condition for a logarithmic derivative of the flowed Xi function backward from de Bruijn's real-zero time to the initial time. Combined with the Rodgers-Tao lower bound for the de Bruijn-Newman constant, the argument shows that this constant equals zero, and hence that the Riemann Hypothesis holds.

---

## Abstract

We develop a parabolic positivity method for the Riemann Xi function along the de Bruijn heat flow (the “Xi flow”). We construct backward Carleman–Kato barriers that propagate nonnegativity of the imaginary part of the negative logarithmic derivative of the flowed Xi function from de Bruijn’s real-zero time back to time t = 0 throughout the upper half-plane.

The barrier follows zero trajectories inside a time-local tube. High-order vanishing weights suppress singularities without dividing by vanishing factors. A relative-derivative calculus enforces extra damping on error terms. Thin temporal shoulders enable interior estimates, and a collision-bridging lemma (via dominated convergence) carries positivity through zero-collision times. On collision-free intervals we close the Carleman absorption by relating the Carleman parameter to the tube thickness using bounds on zero speeds.

A Pick-positivity argument then shows that the logarithmic derivative has no poles in the upper half-plane, so the Xi function has no zeros there; by symmetry, all nontrivial zeros lie on the critical line. Combined with the Rodgers–Tao lower bound for the de Bruijn–Newman constant, we obtain Lambda = 0, and hence the Riemann Hypothesis.

---

## Companion notebook

This repository also includes a companion Jupyter notebook with **stage-by-stage structural checks** for the analytic framework of the paper:

- `rh_xi_backward_parabolic_barrier_checks.ipynb`

The notebook:

- Implements a **per-lemma proof harness** that records which inputs are:
  - mechanised in code (**MECH** – symbolic / toy numerical checks),
  - proved analytically in the paper (**PAPER**),
  - taken as external results (**EXTERNAL**, e.g. de Bruijn, Rodgers–Tao).
- Uses **SymPy** and simple numerical experiments to:
  - verify core **Xi-flow PDE identities** and divergence forms,
  - check **barrier-weight and scaling relations** in simplified models,
  - explore **Pick-positivity / log-derivative** toy examples.
- Writes out `sympy_certificates.json` with “difference = 0” certificates for key symbolic identities.

The notebook is **not a formal proof assistant** and does not mechanise measure-theoretic or deep functional-analytic steps. Its role is to make the algebraic and structural parts of the argument **transparent, testable, and linked back to specific lemmas in the paper.**

## Run the notebook online

You can run the companion Jupyter notebook in the browser to reproduce the symbolic structural verification. No local installation is required.

- [Open in Google Colab](https://colab.research.google.com/github/kschatz/rh-xi-backward-parabolic-barrier/blob/HEAD/rh_xi_backward_parabolic_barrier_checks.ipynb)  
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kschatz/rh-xi-backward-parabolic-barrier/HEAD?filepath=rh_xi_backward_parabolic_barrier_checks.ipynb)
  
---

## Repository contents

- `schatz_riemann_hypothesis_backward_parabolic_positivity_barriers_xi_flow.pdf` – compiled preprint  
- `README.md` – overview, abstract, and citation information  
- `rh_xi_backward_parabolic_barrier_checks.ipynb` – companion Jupyter notebook
- `LICENSE.txt` – licensing terms for this repository (CC BY 4.0)  

---

## Cite this paper

If you use this work, please cite it using one of the formats below:

**BibTeX**
~~~bibtex
@misc{schatz2025rhxibarrier,
  title        = {Riemann Hypothesis: Backward Parabolic Positivity Barriers for the Xi Flow},
  author       = {Schatz, Kevin},
  year         = {2025},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.17636625},
  url          = {https://doi.org/10.5281/zenodo.17636625}
}
~~~

**APA (plain text)**
~~~text
Schatz, K. (2025). Riemann Hypothesis: Backward Parabolic Positivity Barriers for the Xi Flow. Zenodo. https://doi.org/10.5281/zenodo.17636625
~~~

---

## Keywords

Riemann Hypothesis, Riemann zeta function, Riemann Xi function, Xi flow, de Bruijn heat flow, de Bruijn–Newman constant, backward parabolic PDE, Carleman–Kato barrier, positivity, zeros of entire functions, analytic number theory, PDE methods in number theory
