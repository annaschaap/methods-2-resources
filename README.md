# Methods 2: The General Linear Model

## Overview

This course is about regression modelling and its conceptual and mathematical foundations. The main emphasis is on *linear* regression and the *general linear model* (GLM). After familiarizing ourselves with the broader context and goals of linear regression modelling in the first three weeks of the course, we turn to the mathematical foundations of this type (and many other types) of modelling: linear algebra and calculus. The concepts covered here are essential to understanding the methods underlying not just the modelling we use in this course but also the approaches introduced in later semesters. Once the mathematical groundwork is laid, we proceed to applying everything in practice. Ultimately this will take us to generalizations of the GLM like logistic regression.

## Framework and tools

In most practical applications, we will work in the framework of Bayesian inference, which will be introduced at the beginning. Thanks to the modern software tools at our disposal - [R](https://www.r-project.org/) and [Stan](https://mc-stan.org/) - this is much easier nowadays than it used to be. For conceptual and practical reasons, this is the approach of choice. However, for a deeper understanding, we will also cover the *ordinary least squares* (OLS) approach to model fitting.

## Literature

The main textbook for this course is *Regression and Other Stories* by Gelman, Hill, and Vehtari (2020), referenced below. Please get a copy of this. For the mathematical foundations, we will rely on parts of *Essential Mathematics for Political and Social Research* by Gill (2006), also referenced below. You can download the relevant chapters of this via the Royal Library.

Should you want to deepen your knowledge of the mathematical content, I can recommend the two companion books available here: https://minireference.com/.

## Lesson Plan

| Course week | Week of year | Topics and readings                                                                  |
|:-----------:|:------------:|:-------------------------------------------------------------------------------------|
| 1           | 6            | Regression and the GLM: overview, data and measurement, (GHV<sup>1</sup> 1,2)        |
| 2           | 7            | Basic methods, statistical inference (GHV 3)                                         |
| 3           | 8            | Statistical inference (continued), simulation (GHV 4,5)                              |
| 4           | 9            | Math basics: functions, equations, polynomials, logarithms (Gill<sup>2</sup> 1)      |
| 5           | 10           | Linear algebra basics: vectors, matrices, norms, transposition (Gill 3)              |
| 6           | 11           | More linear algebra: geometry, determinants, rank, inversion, eigenvectors (Gill 4)  |
| 7           | 12           | Scalar calculus: derivatives, integrals, fundamental theorem (Gill 5)                |
| 8           | 13           | More calculus: root finding, extrema, Lagrange multipliers, vector calculus (Gill 6) |
| 9           | 15           | Conceptual foundations and history of the GLM, model fitting (GHV 6,7,8)             |
| 10          | 16           | Fitting GLMs: prediction, Bayesian inference (GHV 9)                                 |
| 11          | 17           | Multiple predictors, interactions (GHV 10)                                           |
| 12          | 18           | Model comparison, assumptions and diagnostics (GHV 11)                               |
| 13          | 19           | Transformations, predictive simulations (GHV 12) [no class, just lecture]            |
| 13a         | 21           | Final class to wrap up portfolio writing                                             |

<sup>1</sup> Gelman, A., Hill, J., & Vehtari, A. (2020). *Regression and Other Stories* (Analytical Methods for Social Research). Cambridge: Cambridge University Press. [doi:10.1017/9781139161879](https://doi.org/10.1017/9781139161879)

<sup>2</sup> Gill, J. (2006). *Essential Mathematics for Political and Social Research* (Analytical Methods for Social Research). Cambridge: Cambridge University Press. [doi:10.1017/CBO9780511606656](https://doi.org/10.1017/CBO9780511606656)

## Videos

This whole course (with a few exceptions) [is on YouTube](https://www.youtube.com/playlist?list=PLvJwKACYy5_MTdnrzxx_1sN389dS9OB3S)! These videos are from when the course took place under lockdown conditions. This year, we're going to cover topics in a slightly different order, starting with an introduction to regression modelling before we go into linear algebra and calculus. This means the videos will be less relevant during the first three weeks of the course, but from then on, you can watch them in the order of the playlist.

## Flipped classroom

We will be using a so-called 'flipped classroom' in this course. This means that you are generally expected to have read the literature and wathched the vidoes before coming to the lecture. The purpose of the lecture then is for you to ask questions (the more, the better!) so that we can go over the material again together, deepening and broadening our understanding of it.

## Slack workspace

In order for us to stay in contact, ask questions, and have discussions, there is a Slack workspace dedicated to this course. You will receive an invite link via Brightspace.

## Exam

- Portfolio consisting of 3 assignments
- Each assignment will require you to create an R Markdown notebook
consisting of a mix of text and code.

- Due
  1. End of week 9 (Sunday 5 March, 23:59)
  2. End of week 14 (Monday 10 April, 23:59)
  3. End of week 17 (Sunday 30 April, 23:59)

You will receive a (short) feedback message from us on your portfolio assignments that you can use for improvements before finalizing your hand-ins.
