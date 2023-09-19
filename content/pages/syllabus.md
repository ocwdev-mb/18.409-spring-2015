---
content_type: page
description: This syllabus section provides the course description and information
  on meeting times, prerequisites, course topics, and assessment.
learning_resource_types: []
ocw_type: CourseSection
title: Syllabus
uid: b720ccca-c722-3beb-0eab-c7efa1b4d3aa
---

Course Meeting Times
--------------------

Lectures: 2 sessions / week, 1.5 hours / session

Prerequisites
-------------

[_6.046J / 18.410J Design and Analysis of Algorithms_](/courses/6-046j-design-and-analysis-of-algorithms-spring-2012) or equivalent and [_6.041SC Probabilistic Systems Analysis and Applied Probability_](/courses/6-041sc-probabilistic-systems-analysis-and-applied-probability-fall-2013) or [_18.440 Probability and Random Variables_](/courses/18-440-probability-and-random-variables-spring-2014) or equivalent. You will need a strong background in algorithms, probability and linear algebra.

Description
-----------

Modern machine learning systems are often built on top of algorithms that do not have provable guarantees, and it is the subject of debate when and why they work. In this class, we will focus on designing algorithms whose performance we can rigorously analyze for fundamental machine learning problems. We will cover topics such as: Nonnegative matrix factorization, tensor decomposition, sparse coding, learning mixture models, matrix completion and inference in graphical models. Almost all of these problems are computationally hard in the worst-case and so developing an algorithmic theory is about (1) choosing the right models in which to study these problems and (2) developing the appropriate mathematical tools (often from probability, geometry or algebra) in order to rigorously analyze existing heuristics, or to design fundamentally new algorithms.

Textbook
--------

There is no textbook for this course. Instead, {{% resource_link 47104115-6cc7-bc25-61ea-e5b8d8ed77fc "lecture notes" %}} and {{% resource_link 69ab796e-382c-86b5-a9ed-f1115712f8a5 "readings" %}} are provided.

Course Outline
--------------

*   Nonnegative Matrix Factorization
    *   Qualitative Comparisons to SVD
    *   New Algorithms via Separability
    *   Applications to Topic Models

*   Tensor Decompositions
    *   Tensor Rank, Border Rank and the Rotation Problem
    *   Jennrich's Algorithm and the Generalized Eigenvalue Problem
    *   Learning HMMs
    *   Mixed Membership Models and Community Detection
    *   Cumulants and Independent Component Analysis

*   Sparse Coding
    *   Sparse Recovery, Incoherence and Uncertainty Principles
    *   Alternating Minimization via Approximate Gradient Descent
    *   Sum-of-Squares and Noisy Tensor Decomposition

*   Learning Mixture Models
    *   Expectation Maximization
    *   Clustering in High-dimensions
    *   Method of Moments and Systems of Polynomial Equations

*   Linear Inverse Problems
    *   Nuclear Norm, Atomic Norm and Matrix Completion
    *   Alternating Minimization via Principal Angles
    *   Tensor Prediction and Random CSPs

Assessment
----------

Students will be expected to solve 2 problem sets, and complete a research-oriented final project. This could be either a survey, or original research; students will be encouraged to find connections between the course material and their own research interests.