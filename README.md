# 📚 Educational Jupyter Notebooks: Numerical Optimization and Scientific Computing
![License](https://img.shields.io/github/license/larrywigington/Educational-Notebooks)

A collection of step-by-step Jupyter Notebooks designed to teach **numerical linear algebra**, **optimization algorithms**, and **scientific computing methods** — combining theory, intuition, and clean Python implementations.

---

## 🧠 Project Overview

Understanding numerical algorithms deeply requires more than just code — it demands intuition about convergence, stability, and structure.

These notebooks aim to:
- Walk through **theory first** (intuitive derivations)
- Provide **clear, minimal Python implementations**
- Highlight **common pitfalls** and **best practices**
- Enable hands-on experimentation with **scientific problems**

Built using:
- **Python 3.9+**
- **NumPy**, **SciPy**, **Matplotlib**
- (Optional) **CuPy** for GPU acceleration (in select examples)

---

## 📚 Notebooks Included (v1)

| Notebook | Focus |
|:---------|:------|
| Solving Linear Systems (Ax = b) | LU decomposition, Cholesky factorization, direct methods |
| QR Factorization | Givens rotations and Householder reflections |
| Conjugate Gradient Method (CG) | Solving SPD systems iteratively |
| GMRES and Arnoldi Iteration | Krylov subspace solvers for general systems |
| Simplex Method for Linear Programming | Edge-walking solution method and LP geometry |
| Duality in Linear Programming | Primal-dual relationships, complementary slackness |
| Interior Point Methods (LP) | Barrier functions and central path methods |
| Eigenvalue Problems | Power iteration, inverse iteration, Rayleigh quotient |
| Singular Value Decomposition (SVD) | Low-rank approximations and PCA foundations |
| Multigrid Methods | V-cycle error smoothing for linear systems |

---

## 🛠️ How to Run

### Requirements

```bash
pip install numpy scipy matplotlib jupyter
# (Optional) For GPU demos:
pip install cupy-cuda12x
