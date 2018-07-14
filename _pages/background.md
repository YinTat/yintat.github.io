---
layout: single
permalink: /background.html
title: "Equations on the background"
author_profile: false
header:
  image: background.png
---

{% include base_path %}

The background of this website consists of some equations. These equations excerpt from some of my favourite papers.

### $\phi(G) = O(k) \frac{\lambda_2}{\sqrt{\lambda_k}}$
Cheeger inequality is a fundamental result in spectral graph theory provides a connection between the conductance of a graph and the second eigenvalue of its normalized Laplacian matrix.
We refined inequality, which can be used to provide theoretical justifications of spectral partitioning algorithm.
See the paper [here](https://arxiv.org/abs/1301.5584).

### $\min_{c\in\mathbb{R}^{E}}\|\mathbf{U}^{-1}(f-\mathbf{P}c)\|_{\infty}$
I have been fascinated by the wide applicability of the maximum flow problem since undergraduate. In this paper, we showed that one can solve the maximum flow problem on undirected graphs in almost linear time by "correctly" apply Frank Wolfe algorithm on the equation above.
See the paper [here](https://arxiv.org/abs/1301.5584).

### $\max_{w_{i}\geq0}\ln\det(A_{x}^{\top}W^{1-\frac{2}{q}}A_{x})-(1-\frac{2}{q})\sum_{i=1}^{m}w_{i}$
This formula is the log volume of the "maximum" ellipsoid inside a polytope. Suprisingly, this can be used to develop a faster algorithm for general linear programs and the minimum cost flow problem.
See the paper [here](https://arxiv.org/abs/1301.5584).

### $\mathbf{M}\approx_{\gamma}\left[\begin{array}{cc} \mathbf{I} & \mathbf{0}\\\mathbf{Z}_{FF}^{(k)}\mathbf{M}_{FC} & \mathbf{I}\end{array}\right]\left[\begin{array}{cc}\mathbf{M}_{FF} & \mathbf{0}\\\mathbf{0} & \widetilde{\mathrm{Sc}}(\mathbf{M},F)\end{array}\right]\left[\begin{array}{cc}\mathbf{I} & \mathbf{M}_{CF}\mathbf{Z}_{FF}^{(k)}\\0 & \mathbf{I}\end{array}\right]$
The problem of solving symmetric diagonally dominant matrix has been studied for many centuries. In 2003, Spielman and Teng showed how to solve such matrix in nearly linear time. Ever since we have been asking what makes these matrices easy to solve. Turns out, one explanation is that the class of such matrices is closed under Schur complement and can be represented by a sum of PSD matrices with small support. Using this, we show how to solve such matrix in linear time with nearly linear time preprocessing.
See the paper [here](https://arxiv.org/abs/1512.01892).

### $D_{t}\frac{dx}{dt} & =-\frac{1}{2}g(x)^{-1}\mathrm{Tr}\left[g(x)^{-1}Dg(x)\right]$
Sampling from the uniform distribution of a given convex set is a fundamental problem in convex geometry. Many existing algorithms take at least linear number of iterations to generate a sample and hence impractical for large-scale problem. It turns out one can generate random sample very efficiently using the Riemannian Hamiltonian dynamic.
See the paper [here](https://arxiv.org/abs/1710.06261).

### $\mathbb{P}_{x\sim p}(f(x)\geq\mathbb{E}f(x)+t)\leq e^{-O(t^{2})/(t+\sqrt{n})}$
