---
layout: page
title: "A Second Course in Algorithms"
description: "An advanced algorithms course based on Tim Roughgarden's Stanford CS261 (Winter 2016)."
category: COS          # Computer Science group
importance: 3          # smaller number => appears earlier within COS
img: /assets/courses/A-Second-Course-In-Algorithms/Thumb-1.jpg
permalink: /courses/a-second-course-in-algorithms/
---

## A Second Course In Algorithms
Recently I’ve been studying game theory, and in particular I became curious about how **linear programming** appears in the proof of von Neumann’s **minimax theorem**. In parallel, I was learning about **machine learning**, where I ran into the **AdaBoost** paradigm and also encountered **multiplicative weight updates** in the context of multi-armed bandit learning. All of these topics felt strangely related.

Another question that caught my attention was the following: 

>> In a repeated game, what happens if both players use **regret-free (no-regret)** learning algorithms?

My first intuition was that in **zero-sum games** this should somehow converge to an equilibrium, while in more general games it might fail to converge or exhibit more complicated behavior.

I still do not fully understand all of these connections, but they are exactly the reasons this course appealed to me: it brings together **linear programming, duality, game-theoretic ideas, and multiplicative weights** in one coherent framework. My personal goal is to work through the entire course over the next 90 days.


## Overview

*A Second Course in Algorithms* is an advanced follow-up to a standard undergraduate algorithms class. Based on Tim Roughgarden’s Stanford **CS261 (Winter 2016)**, the course focuses on powerful tools and paradigms for designing and analyzing algorithms beyond the basics of CS1/CS2 and a first algorithms course.

## Topics / Syllabus

**Part I – Combinatorial optimization**

- Maximum flow: Ford–Fulkerson, Edmonds–Karp, Dinic’s algorithm  
- Minimum \(s\)-\(t\) cuts and applications (e.g., image segmentation)  
- Reductions between max flow, min cut, and bipartite matching  
- Minimum-cost bipartite matching and the Hungarian algorithm  
- Generalizations: min-cost flow, non-bipartite matching, etc. 

**Part II – Linear programming and duality**

- Modeling optimization problems as linear programs  
- Geometric intuition for LPs and basic examples  
- LP duality: constructing duals, weak/strong duality, complementary slackness  
- Max-flow/min-cut via duality  
- Applications to matching, game theory (minimax theorem), and algorithm design  
- Overview of algorithms for LP: simplex, ellipsoid, interior-point methods

**Part III – Online algorithms and multiplicative weights**

- Online decision-making and regret minimization  
- The multiplicative weights update method and its analysis  
- Applications to zero-sum games, linear classifiers, and fast approximate flows  
- Classic online problems: online scheduling, online Steiner tree, online bipartite matching  

**Part IV – Algorithms for NP-hard problems**

- Introduction to approximation algorithms and approximation ratios  
- Approximation for scheduling, knapsack, Steiner tree, set cover, influence maximization  
- Metric TSP and Christofides’ algorithm  
- LP-based approximation: set cover, vertex cover via LP rounding and primal–dual methods  
- Randomized algorithms: tools (linearity of expectation, Markov/Chebyshev/Chernoff) and applications (e.g., hashing, MAX-3SAT)  
- “Beating brute force”: fixed-parameter tractability and clever exact algorithms for NP-hard problems  
- Semidefinite programming and Max-Cut: SDP relaxations and randomized rounding 

---

## Prerequisites

This is not an introductory algorithms class. It is intended for students who:

- Have completed a **first course in algorithms** (e.g., Stanford CS161 or equivalent), including asymptotic analysis, basic graph algorithms, dynamic programming, and NP-completeness.  
- Are comfortable with **discrete mathematics** (graphs, combinatorics, proofs by induction and contradiction).
- Have some familiarity with **probability** (expectations, basic inequalities) and **linear algebra** (vectors, matrices, linear systems).

---

## Main resources

- **Lecture playlist (primary resource)**  
  *Tim Roughgarden – A Second Course in Algorithms (Stanford CS261, Winter 2016)*  
  [YouTube playlist](https://www.youtube.com/playlist?list=PLEGCF-WLh2RJh2yDxlJJjnKswWdoO8gAc)

- **Course home page (original Stanford CS261)**  
  Contains lecture notes (one PDF per lecture), problem sets, and a detailed schedule.  
  [CS261: A Second Course in Algorithms – Winter 2016](https://timroughgarden.org/w16/w16.html)






