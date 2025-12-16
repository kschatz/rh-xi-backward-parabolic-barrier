# Riemann Hypothesis: Backward Parabolic Positivity Barriers for the Xi Flow

**Author:** Kevin Schatz

**DOI:** [10.5281/zenodo.17636625](https://doi.org/10.5281/zenodo.17636625)<br>
**PDF:** [Download preprint](https://zenodo.org/records/17636625/files/schatz_riemann_hypothesis_backward_parabolic_positivity_barriers_xi_flow.pdf)

## Overview

We develop a parabolic positivity method for the Riemann Xi function along the de Bruijn heat flow (the Xi flow). Using backward Carleman–Kato barriers, we propagate a positivity condition for the imaginary part of the negative logarithmic derivative of the flowed Xi function from de Bruijn’s real-zero time back to the initial time. Combined with the Rodgers–Tao lower bound for the de Bruijn–Newman constant, this yields that the constant equals zero, and hence that the Riemann Hypothesis holds.

---

## Abstract

We develop a parabolic positivity method for the Riemann Xi function based on backward Carleman–Kato barriers for the de Bruijn heat flow (the “Xi flow”). Writing the de Bruijn deformation of the completed zeta function as a time-dependent Xi function obtained by heat-flow evolution, we construct a backward barrier that propagates nonnegativity of the imaginary part of the negative logarithmic derivative of the flowed Xi function from de Bruijn’s real-zero time back to the initial time, for all points in the upper half-plane.

The barrier is built using a time-local tube around the moving zeros, together with a weight that vanishes algebraically of order greater than two, which suppresses the poles of the logarithmic derivative without dividing by a vanishing factor. Inside this tube, we introduce a relative-derivative calculus that forces all commutator error terms to carry a squared weight factor and to be dominated by the positive Carleman bulk contribution. Thin time shoulders allow the backward Carleman estimate to act on an interior time slab, and a collision-bridging lemma, based on dominated convergence, propagates the positivity condition across all zero-collision times.

On each collision-free time component, we close the Carleman absorption under an explicit cubic relation between the Carleman parameter and the tube thickness, with constants depending only on an upper bound for the zero speeds. Iterating backward from de Bruijn’s real-zero time yields nonnegativity of the imaginary part of the negative logarithmic derivative of the Xi function in the upper half-plane at the initial time. A Pick-positivity argument then shows that the negative logarithmic derivative has no poles in the upper half-plane, and therefore that the Xi function has no zeros there. By evenness, all nontrivial zeros lie on the critical line. Combined with the Rodgers–Tao lower bound for the de Bruijn–Newman constant, this gives that the constant equals zero, and hence the Riemann Hypothesis.

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

- <a href="schatz_riemann_hypothesis_backward_parabolic_positivity_barriers_xi_flow.pdf">
  schatz_riemann_hypothesis_backward_parabolic_positivity_barriers_xi_flow.pdf – compiled preprint</a>
- <a href="https://github.com/kschatz/rh-xi-backward-parabolic-barrier/blob/main/rh_xi_backward_parabolic_barrier_checks.ipynb">
  rh_xi_backward_parabolic_barrier_checks.ipynb – companion Jupyter notebook</a>
- `LICENSE.txt` – licensing terms for this repository (CC BY 4.0)
- `README.md` – overview, abstract, and citation information

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
