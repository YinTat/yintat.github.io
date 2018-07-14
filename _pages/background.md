---
layout: single
permalink: /background.html
title: "Equations on the background"
author_profile: false
header:
  image: background_clear.png
---

{% include base_path %}

The background of this website consists of some equations. These equations excerpt from some of my favourite papers.

### $\phi(G) = O(k) \frac{\lambda_2}{\sqrt{\lambda_k}}$
This is the first theory paper. Cheeger inequality is a fundamental result in spectral graph theory. This inequality is not tight in many graphs appear in practice. In the [paper](https://arxiv.org/abs/1301.5584), we refined inequality, which can be used to provide theoretical justifications of spectral partitioning algorithm.

### $\min_{c\in\mathbb{R}^{E}}\|\mathbf{U}^{-1}(f-\mathbf{P}c)\|_{\infty}$
I have been fascinated by the wide applicability of the maximum flow problem since undergraduate. In the [paper](https://arxiv.org/abs/1301.5584), we showed that one can solve the maximum flow problem on undirected graphs in almost linear time by "correctly" apply Frank Wolfe algorithm on the equation above.

### $\max_{w_{i}\geq0}\ln\det(A_{x}^{\top}W^{1-\frac{2}{q}}A_{x})-(1-\frac{2}{q})\sum_{i=1}^{m}w_{i}$
My usual strategy to solve a problem is by playing around formulas. Aaron and I came up with [this formula](https://arxiv.org/abs/1301.5584) and used that solve linear programs faster. At that time we had no idea of the meaning of such formula. A few years later, we noticed from a paper by Richard and Michael that the maximizer $w$ is exactly the $\ell_p$ Lewis weight of the matrix $A_x$ which is defined in Banach space theory many decades ago!

<h3> $\mathbf{M}\approx_{\gamma}\left[\begin{array}{cc} \mathbf{I} & \mathbf{0}\\\mathbf{Z}_
  {FF}^{(k)}\mathbf{M}_{FC} & \mathbf{I}\end{array}\right]\left[\begin{array}{cc}\mathbf{M}_{FF} & \mathbf{0}\\\mathbf{0} & \widetilde{\mathrm{Sc}}(\mathbf{M},F)\end{array}\right]\left[\begin{array}{cc}\mathbf{I} & \mathbf{M}_{CF}\mathbf{Z}_{FF}^{(k)}\\0 & \mathbf{I}\end{array}\right]$</h3>
The problem of solving symmetric diagonally dominant matrix has been studied for many centuries. In 2003, Spielman and Teng showed how to solve such matrix in nearly linear time. Ever since we have been asking what makes these matrices easy to solve. Turns out, one explanation is that the class of such matrices is closed under Schur complement and can be represented by a sum of PSD matrices with small support. Using this, we show how to solve such matrix in linear time with nearly linear time preprocessing.
See the paper [here](https://arxiv.org/abs/1512.01892).

### $D_{t}\frac{dx}{dt} =-\frac{1}{2}g(x)^{-1}\mathrm{Tr}\left(g(x)^{-1}Dg(x)\right)$
Sampling from the uniform distribution of a given convex set is a fundamental problem in convex geometry. Many existing algorithms take at least linear number of iterations to generate a sample and hence impractical for large-scale problem. It turns out one can generate random sample very efficiently using the Riemannian Hamiltonian dynamic.
See the paper [here](https://arxiv.org/abs/1710.06261).

### $\mathbb{P}_{x\sim p}(f(x)\geq\mathbb{E}f(x)+t)\leq e^{-O(t^{2})/(t+\sqrt{n})}$
A few years ago, I was told that one may win a Fields medal by solving Kannan-Lovász-Simonovits Conjecture, a problem that has deep connections in algorithmic convex geometry and concentration of measure. This is how I got interested in the problems. Despite I am not able to solve the problem, Santosh and I get the best estimate on the problem and gave a tight estimate for a stronger statement. The equation above is a corollary of that result, which shows any Lipschitz function $f$ concentrated around its mean under isotropic log-concave distribution $p$.
See the paper [here](https://arxiv.org/abs/1712.01791).

### $\sum_{u\in T}w_{u}\sum_{i\geq1}(x_{u,i}+\delta)\log(x_{u,i}+\delta)$
A few years ago, I was told that one may win a Fields medal by solving Kannan-Lovász-Simonovits Conjecture, a problem that has deep connections in algorithmic convex geometry and concentration of measure. This is how I got interested in the problems. Despite I am not able to solve the problem, Santosh and I get the best estimate on the problem and gave a tight estimate for a stronger statement. The equation above is a corollary of that result, which shows any Lipschitz function $f$ concentrated around its mean under isotropic log-concave distribution $p$.
See the paper [here](https://arxiv.org/abs/1711.01085).
