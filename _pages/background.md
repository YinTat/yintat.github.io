---
layout: single
permalink: /background.html
title: "Equations on the background"
author_profile: false
header:
  image: background_clear.png
---

{% include base_path %}

The background of this website consists of some equations, excerpt from some of my papers.

### $\phi(G) = O(k) \frac{\lambda_2}{\sqrt{\lambda_k}}$
This is the my theory paper. Cheeger inequality is a fundamental result in spectral graph theory, but it is not tight in many graphs appear in practice. In the [paper](https://arxiv.org/abs/1301.5584), we refined the inequality and used it to provide theoretical justifications of spectral partitioning algorithm.

### $\min_{c\in\mathbb{R}^{E}}\|\mathbf{U}^{-1}(f-\mathbf{P}c)\|_{\infty}$
I have been fascinated by the wide applicability of the maximum flow problem since undergraduate. In the [paper](https://arxiv.org/abs/1301.5584), we showed that one can solve the maximum flow problem on undirected graphs in almost linear time by "correctly" apply Frank Wolfe algorithm on the equation above.

### $\max_{w_{i}\geq0}\ln\det(A_{x}^{\top}W^{1-\frac{2}{q}}A_{x})-(1-\frac{2}{q})\sum_{i=1}^{m}w_{i}$
My usual strategy to solve a problem is by playing around formulas. Aaron and I came up with [this formula](https://arxiv.org/abs/1301.5584) and used that solve linear programs faster. At that time we had no idea of the meaning of such formula. A few years later, we noticed from a paper by Richard and Michael that the maximizer $w$ is exactly the $\ell_p$ Lewis weight of the matrix $A_x$ which is defined in Banach space theory many decades ago!

<h3> $\mathbf{M}\approx_{\gamma}\left[\begin{array}{cc} \mathbf{I} & \mathbf{0}\\\mathbf{Z}_
  {FF}^{(k)}\mathbf{M}_{FC} & \mathbf{I}\end{array}\right]\left[\begin{array}{cc}\mathbf{M}_{FF} & \mathbf{0}\\\mathbf{0} & \widetilde{\mathrm{Sc}}(\mathbf{M},F)\end{array}\right]\left[\begin{array}{cc}\mathbf{I} & \mathbf{M}_{CF}\mathbf{Z}_{FF}^{(k)}\\0 & \mathbf{I}\end{array}\right]$</h3>
The problem of solving symmetric diagonally dominant matrix has been studied for many centuries. In 2003, Spielman and Teng showed how to solve such matrix in nearly linear time. Ever since we have been asking what makes these matrices easy to solve. One explanation is  that the family of such matrices is closed under Schur complement and can be represented by a sum of PSD matrices with small support. Using this, [we](https://arxiv.org/abs/1512.01892) showed how to solve such matrix in linear time with nearly linear time preprocessing.

### $D_{t}\frac{dx}{dt} =-\frac{1}{2}g(x)^{-1}\mathrm{Tr}\left(g(x)^{-1}Dg(x)\right)$
Sampling from the uniform distribution of a given convex set is a fundamental problem in convex geometry. Many existing algorithms take at least linear number of iterations to generate a sample and hence impractical for large-scale problem. [It turns out](https://arxiv.org/abs/1710.06261). one can generate random sample very efficiently using the Riemannian Hamiltonian dynamic.

### $\mathbb{P}_{x\sim p}(f(x)\geq\mathbb{E}f(x)+t)\leq e^{-O(t^{2})/(t+\sqrt{n})}$
A few years ago, I was told that one may win a Fields medal by solving Kannan-Lovász-Simonovits Conjecture, a problem that has deep connections in algorithmic convex geometry and concentration of measure. This is how I got interested in the problems. Despite I am not able to solve the problem, Santosh and I got the best estimate on the problem and gave a [tight estimate](https://arxiv.org/abs/1712.01791) for a stronger statement. The equation above is a corollary of that result, which shows any 1-Lipschitz function $f$ concentrates around its mean under any isotropic log-concave distribution $p$.


### $\sum_{u\in T}w_{u}\sum_{i\geq1}(x_{u,i}+\delta)\log(x_{u,i}+\delta)$
To be honest, I still don't understand [this equation](https://arxiv.org/abs/1711.01085) and I hope someone can explain this to me for general graphs. Maybe this is simply a wrong direction.


<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<!-- horizontal -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7216078004228924"
     data-ad-slot="1584892646"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>
<script>
     (adsbygoogle = window.adsbygoogle || []).push({});
</script>
