---
layout: page
title: "Introduction to Theoretical Machine Learning"
description: "A mathematically grounded introduction to machine learning based on Shalev-Shwartz & Ben-David's book Understanding Machine Learning."
category: COS          # shows up under your COS group
importance: 1          # smaller number => appears earlier within COS
img: /assets/courses/introduction-to-theoretical-machine-learning/intro-theoretical-ml-thumb.jpg
permalink: /courses/introduction-to-theoretical-machine-learning/
---

**Overview**

This course is a theoretical introduction to machine learning, focusing on precise learning models, generalization guarantees, and the algorithmic principles behind modern methods. The main reference is

> **Shai Shalev-Shwartz & Shai Ben-David, _Understanding Machine Learning: From Theory to Algorithms_ (Cambridge University Press, 2014).**

A free PDF of the book is available here:

- [Understanding Machine Learning: From Theory to Algorithms (PDF)](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/understanding-machine-learning-theory-algorithms.pdf)

The course is inspired by Shai Ben-David’s theoretical machine learning courses and follows the structure of the book fairly closely.

---

## Main resources

- **Primary textbook**  
  Shai Shalev-Shwartz & Shai Ben-David,  
  _Understanding Machine Learning: From Theory to Algorithms_, Cambridge University Press, 2014.  
  This book develops the foundations of statistical learning theory and connects them to concrete algorithms: PAC learning, VC dimension, generalization bounds, linear predictors, convex learning problems, regularization, and more.

- **Video lectures (Shai Ben-David)**  
  [Machine Learning Theory / Understanding Machine Learning – YouTube playlist](https://www.youtube.com/watch?v=b5NlRg8SjZg&list=PLPW2keNyw-usgvmR7FTQ3ZRjfLs5jT4BO)  
  A full lecture series that tracks the book and develops the main concepts and proofs in detail (PAC learning, VC theory, linear predictors, margin bounds, convex optimization, etc.).

---

## Prerequisites

Students are expected to have:

- Solid **linear algebra** (vector spaces, norms, inner products, eigenvalues, PSD matrices).  
- Basic **probability theory** (random variables, expectation, variance, laws of large numbers, basic inequalities).  
- Comfort with **rigorous proofs** (induction, contradiction, epsilon–delta style arguments).  
- Some familiarity with algorithms / complexity is helpful but not strictly required.

---

## Topics (tentative outline)

The course follows the structure of _Understanding Machine Learning_ and covers, for example:

### Foundations of learning

- The learning problem, empirical risk minimization (ERM), and overfitting  
- PAC learning: realizable and agnostic settings  
- Generalization via uniform convergence  
- Bias–complexity trade-off and sample complexity  
- VC dimension and Sauer’s lemma  
- Non-uniform learnability and structural risk minimization  
- Computational aspects of learning: efficient vs inefficient learners

### From theory to algorithms

- Linear predictors and margin-based generalization  
- Perceptron, logistic regression, and other linear methods  
- Model selection and validation (train/validation/test, cross-validation)  
- Convex learning problems and optimization  
- Regularization and algorithmic stability  
- Stochastic gradient descent (SGD) and online-to-batch conversion  
- Support vector machines (SVMs) and large-margin classification  
- Kernel methods and feature maps

### Additional topics (time permitting)

- Online learning and regret minimization  
- Ensemble methods and boosting  
- Clustering from a theoretical perspective  
- Theoretical views on neural networks and overparameterization (as time and interest allow)

---
## Useful links

- Shai Ben-David – Foundations of Learning Theory (MPI talks)  
  A three-part mini-course at the Max Planck Institute on core ideas in statistical learning theory: VC dimension, the uniform convergence property, and non-uniform learnability. These talks are a great complement to the textbook and to the material on PAC learning and VC theory discussed in this course.

  - **Part 1 – VC dimension and the uniform convergence paradigm**  
    Introduction to the PAC framework, hypothesis classes, and VC dimension as a measure of complexity. Explains how uniform convergence connects the complexity of a hypothesis class to generalization guarantees.  
    [Watch Part 1](https://www.youtube.com/watch?v=PazAnVWEq-0&t=5191s)

  - **Part 2 – More on VC dimension and generalization**  
    Continues the discussion of VC dimension and uniform convergence, with more examples and intuition on why VC dimension controls learnability and sample complexity.  
    [Watch Part 2](https://www.youtube.com/watch?v=-Ypw18j7LIs)

  - **Part 3 – Non-uniform learnability and beyond**  
    Discusses non-uniform learnability, where different hypotheses within the same class can have different sample-complexity behavior, and how this refines the usual uniform convergence picture. Connects these ideas back to practical learning scenarios.  
    [Watch Part 3](https://www.youtube.com/watch?v=_Q9gXuM7vbc&t=1992s)

