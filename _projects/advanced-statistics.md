---
layout: page
title: Advanced Statistics
description: Notes, readings, and problem sets from my Advanced Statistics course.
category: Etc          # or COS/Etc — choose the group you want it under
importance: 1           # smaller number = appears earlier within its group
img: /assets/courses/advanced-statistics/thumb.jpg
permalink: /courses/advanced-statistics/
---

# Advanced Statistics
An ongoing graduate course in Sharif University on advanced topics in statistics, following much of the material from Trevor Hastie and Bradley Efron’s *Computer Age Statistical Inference* ([book/site](https://hastie.su.domains/CASI/)).  
Lectured by [Kasra Alishahi](https://www.researchgate.net/profile/Kasra-Alishahi).
## Overview

**Part I — Classical Inference**
- Algorithms and inference  
- Frequentist inference  
- Bayesian inference  
- Fisherian inference and maximum likelihood estimation (MLE)  
- Parametric models and the exponential family  

**Part II — Dawn of the Computer Age**
- Empirical Bayes  
- James–Stein estimators and ridge regression  
- Generalized linear models (GLMs) and regression trees  
- Survival analysis and the EM algorithm  
- Jackknife and bootstrap  
- Resampling-based confidence intervals  
- Cross-validation and prediction-error estimation  
- Bayesian inference and MCMC  
- Post-war statistical methods and inference  

**Part III — The 21st Century**
- Multiple testing and the false discovery rate (FDR)  
- Sparse modeling and the LASSO  
- Random forests and boosting  
- Neural networks and deep learning  
- Support vector machines (SVMs) and kernel methods  
- Post-selection inference  
- Empirical-Bayes estimation strategies  

## Reading List
- [Computer Age Statistical Inference](https://hastie.su.domains/CASI/index.html)

- [A Brief History of Statistics in Three and One-Half Chapters](https://www.maths.tcd.ie/~donmoore/project/project/Write%20up/final!!!/final_draft/brief%20history%20statistics.pdf)

- [On the Mathematical Foundations of Theoretical Statistics](https://khaled-alk.github.io/assets/courses/advanced-statistics/On-the-Mathematical-Foundations-of-Theoretical-Statistics.pdf). R. A. Fisher’s 1922 paper on the math foundations of theoretical statistics—covering key ideas like estimation, likelihood, and efficiency that still show up everywhere today. It is rather unbelievable how he managed to come up with all these fascinating ideas!

- Nice discussion on [In what sense is the Jeffreys prior invariant?](https://math.stackexchange.com/questions/210607/in-what-sense-is-the-jeffreys-prior-invariant)

- [R. A. Fisher in the 21st Century](https://www.jstor.org/stable/2676745?seq=1). Bradly Efron article on R. A. Fisher’s lasting impact on statistics.

- [Estimating the Number of Unsen Species: How Many Words Did Shakespeare Know?](https://www.jstor.org/stable/2335721). Bradley Efron borrows the same “unseen species” trick R.A. Fisher used in ecology—estimating how many things you *didn’t* observe—to tackle a fun question: how big was Shakespeare’s vocabulary?!


- Susan Holmes, Carl Morris, and Robert Tibshirani (2003).
  *Bradley Efron: A Conversation with Good Friends*.
  _Statistical Science_, 18(2), 268–281.  
  [Original PDF (English)](https://khaled-alk.github.io/assets/courses/advanced-statistics/efron-conversation-good-friends-2003.pdf)  
  [Persian translation – translated by Kasra Alishahi](https://khaled-alk.github.io/assets/courses/advanced-statistics/efron-conversation-good-friends-2003-fa-alishahi.pdf)




## Useful Links

- Rob Tibshirani and friends (Trevor Hastie, John Cherian, Stefan Wager, Ryan Tibshirani) interview authors of seminal papers in the field of Statistics. This is part of a project from Stanford's Stat 319 class in Winter 2024 to discuss important papers in the field. Please visit the website below to find the original papers, presentation slides, and summaries.  
  [Interviews playlist](https://www.youtube.com/playlist?list=PLt_pNkbycxqahVksaNnjz3M6759xHIZ-r) · [Project website](https://ledaliang.github.io/journalclub/)

 - [Kullback–Leibler divergence](https://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence) is a common “distance-like” way to compare probability distributions (even though it isn’t always a true metric). If you’ve seen a bit of information theory, it’ll feel pretty familiar.  
What’s nice is that it also shows up naturally when you look at Fisher’s work on MLE (see Exercise 7 in PS1). This video is a helpful, intuitive illustration of what’s going on.[Watch on Youtube](https://www.youtube.com/watch?v=KHVR587oW8I&t=69s)


- Useful videos on James–Stein paradox  
  For a long time, many statisticians thought the maximum likelihood estimator (MLE) was essentially the “best possible” estimator: in many classical models it is efficient and was believed to be admissible (there is no other estimator that strictly dominates it everywhere). Results like the Cramér–Rao lower bound and Fisher’s work on MLE supported this view.

  Stein’s paradox shows that this intuition can fail in higher dimensions. When we estimate the mean of a multivariate normal distribution in three or more dimensions, the usual MLE (the sample mean) is actually inadmissible: the James–Stein estimator shrinks all coordinates toward a common point and achieves a strictly smaller total mean squared error for every true parameter vector. This is why it is called a “paradox”: we can improve our estimates of several unrelated quantities by pulling them toward each other.

  - **The weirdest paradox in statistics (and machine learning)** – An intuitive introduction to Stein’s paradox and the James–Stein estimator, with geometric explanations, discussion of shrinkage and the bias–variance tradeoff, and examples from modern machine learning.  
    [Watch on YouTube](https://www.youtube.com/watch?v=cUqoHQDinCM)

  - **Why James–Stein estimator dominates ordinary MLE** – A more technical follow-up that works through the calculations showing that the James–Stein estimator has strictly lower mean squared error than the ordinary MLE in dimension three or higher, and explains why this improvement disappears in 1–2 dimensions.  
    [Watch on YouTube](https://www.youtube.com/watch?v=3ne9yghOtw8)


## Materials
- [Problem set 1](https://www.overleaf.com/read/jvqhrjcgpbbd#024ec6) 
