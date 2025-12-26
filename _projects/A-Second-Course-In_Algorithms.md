---
layout: page
title: "A Second Course in Algorithms"
description: "An advanced algorithms course based on Tim Roughgarden's Stanford CS261 (Winter 2016)."
category: COS          # Computer Science group
importance: 1          # smaller number => appears earlier within COS
img: /assets/courses/a-second-course-in-algorithms/thumb.jpg
permalink: /courses/a-second-course-in-algorithms/
---

**Overview**

*A Second Course in Algorithms* is an advanced follow-up to a standard undergraduate algorithms class. Based on Tim Roughgarden’s Stanford **CS261 (Winter 2016)**, the course focuses on powerful tools and paradigms for designing and analyzing algorithms beyond the basics of CS1/CS2 and a first algorithms course. :contentReference[oaicite:0]{index=0}  

The playlist covers four major themes:

- **Combinatorial optimization:** maximum flows, minimum cuts, bipartite matching, min-cost flows, and related network problems.
- **Linear programming and duality:** modeling optimization problems as LPs, geometric intuition, duality, and applications to flows, matching, and game theory.
- **Online and learning-style algorithms:** the multiplicative weights framework, regret, and classic online problems such as scheduling, Steiner tree, and online bipartite matching.
- **Algorithms for NP-hard problems:** approximation algorithms for TSP, set cover, vertex cover, and others; randomized algorithms; semidefinite programming and the Max-Cut problem. :contentReference[oaicite:1]{index=1}  

The goal is twofold: (1) to give a “final algorithms course” packed with broadly useful techniques, and (2) to provide a bridge to research-level work in algorithms, optimization, and complexity. :contentReference[oaicite:2]{index=2}  

---

## Main resources

- **Lecture playlist (primary resource)**  
  *Tim Roughgarden – A Second Course in Algorithms (Stanford CS261, Winter 2016)*  
  [YouTube playlist](https://www.youtube.com/playlist?list=PLEGCF-WLh2RJh2yDxlJJjnKswWdoO8gAc)

- **Course home page (original Stanford CS261)**  
  Contains lecture notes (one PDF per lecture), problem sets, and a detailed schedule.  
  [CS261: A Second Course in Algorithms – Winter 2016](https://timroughgarden.org/w16/w16.html) :contentReference[oaicite:3]{index=3}  

---

## Prerequisites

This is not an introductory algorithms class. It is intended for students who:

- Have completed a **first course in algorithms** (e.g., Stanford CS161 or equivalent), including asymptotic analysis, basic graph algorithms, dynamic programming, and NP-completeness. :contentReference[oaicite:4]{index=4}  
- Are comfortable with **discrete mathematics** (graphs, combinatorics, proofs by induction and contradiction).
- Have some familiarity with **probability** (expectations, basic inequalities) and **linear algebra** (vectors, matrices, linear systems).

---

## Topics / Syllabus (inspired by CS261)

### Part I – Combinatorial optimization

- Maximum flow: Ford–Fulkerson, Edmonds–Karp, Dinic’s algorithm  
- Minimum \(s\)-\(t\) cuts and applications (e.g., image segmentation)  
- Reductions between max flow, min cut, and bipartite matching  
- Minimum-cost bipartite matching and the Hungarian algorithm  
- Generalizations: min-cost flow, non-bipartite matching, etc. :contentReference[oaicite:5]{index=5}  

### Part II – Linear programming and duality

- Modeling optimization problems as linear programs  
- Geometric intuition for LPs and basic examples  
- LP duality: constructing duals, weak/strong duality, complementary slackness  
- Max-flow/min-cut via duality  
- Applications to matching, game theory (minimax theorem), and algorithm design  
- Overview of algorithms for LP: simplex, ellipsoid, interior-point methods :contentReference[oaicite:6]{index=6}  

### Part III – Online algorithms and multiplicative weights

- Online decision-making and regret minimization  
- The multiplicative weights update method and its analysis  
- Applications to zero-sum games, linear classifiers, and fast approximate flows  
- Classic online problems: online scheduling, online Steiner tree, online bipartite matching :contentReference[oaicite:7]{index=7}  

### Part IV – Algorithms for NP-hard problems

- Introduction to approximation algorithms and approximation ratios  
- Approximation for scheduling, knapsack, Steiner tree, set cover, influence maximization  
- Metric TSP and Christofides’ algorithm  
- LP-based approximation: set cover, vertex cover via LP rounding and primal–dual methods  
- Randomized algorithms: tools (linearity of expectation, Markov/Chebyshev/Chernoff) and applications (e.g., hashing, MAX-3SAT)  
- “Beating brute force”: fixed-parameter tractability and clever exact algorithms for NP-hard problems  
- Semidefinite programming and Max-Cut: SDP relaxations and randomized rounding :contentReference[oaicite:8]{index=8}  

---

## How this page can be used

- As a **self-study guide**, using the playlist and CS261 notes as the main material.  
- As a **course shell** if you later teach your own “Second Course in Algorithms”: you can add your own:
  - lecture notes or slides,  
  - problem sets and solutions,  
  - links to related courses (e.g., randomized algorithms, online algorithms, or approximation algorithms).

You can extend this page with sections like **“Lecture notes”**, **“Homework”**, or **“Further reading”** once you start using it actively.
::contentReference[oaicite:9]{index=9}
