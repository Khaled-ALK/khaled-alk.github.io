---
layout: page
title: "Convex Optimization I"
description: "Core ideas, theory, and algorithms for convex optimization (Boyd-style)."
category: ETC
importance: 2
img: /assets/courses/convex-optimization-i/convex_thumb_1.png
permalink: /courses/convex-optimization-i/
---

## Overview
(Write your short description here: what the course covers, who it’s for, and what you want to get out of it.)

## Topics / Syllabus
1. **Introduction**
   - What makes optimization “convex”
   - Examples, modeling mindset, applications

2. **Convex sets**
   - Affine sets, convex hulls, cones
   - Norm balls, halfspaces, polyhedra
   - Separating hyperplane intuition

3. **Convex functions**
   - Definitions and first-order conditions
   - Composition rules
   - Common convex/concave functions
   - Conjugates (optional but very useful)

4. **Convex optimization problems**
   - Standard form and epigraph form
   - Constraints, feasibility, reformulations
   - Modeling patterns (slack variables, piecewise-linear, max-of-affine, norms)

5. **Important problem classes**
   - Linear programs (LP)
   - Quadratic programs (QP)
   - Second-order cone programs (SOCP)
   - Semidefinite programs (SDP)
   - Geometric programs (GP) / log-transform tricks (optional)

6. **Duality**
   - Lagrangian, dual function, dual problem
   - Weak/strong duality, Slater’s condition
   - Dual interpretation and bounds

7. **Optimality conditions**
   - KKT conditions
   - Complementary slackness
   - Sensitivity / perturbation interpretation (optional)

8. **Algorithms: first-order methods**
   - Gradient descent on smooth convex objectives
   - Subgradient method for nonsmooth problems
   - Proximal gradient / projected gradient
   - Basic convergence ideas (rates at a high level)

9. **Algorithms: Newton and interior-point methods**
   - Newton’s method for unconstrained problems
   - Barrier method and central path
   - Primal-dual interior-point ideas (high-level)

10. **Decomposition and large-scale optimization**
   - Dual decomposition
   - ADMM (Alternating Direction Method of Multipliers)
   - Distributed / splitting intuition

11. **Applications / modeling case studies** (choose a few)
   - Least squares, ridge/LASSO-style regularization
   - Portfolio optimization
   - Classification/regression (convex surrogates)
   - Control / signal processing examples
   - Robust optimization (optional)

## References (free PDFs)
- **Boyd & Vandenberghe — Convex Optimization (book PDF)**  
  https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf

- **Boyd — EE364a/Convex Optimization course materials (handouts/slides/notes vary by year)**  
  https://web.stanford.edu/~boyd/

## Problem Sets
- **PS1:** (link)
- **PS2:** (link)
- **PS3:** (link)

## Projects (optional)
- (Project idea / link)

## Software / Tools (optional)
- **Python:** CVXPY (convex modeling), NumPy/SciPy, Matplotlib
- **MATLAB:** CVX (if you use MATLAB)
- (Add install notes / preferred workflow later)

## Extra Links
- (Videos, other university notes, useful blog posts)
