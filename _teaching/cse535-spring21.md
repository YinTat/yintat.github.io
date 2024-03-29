---
layout: single
title: "CSE 535: Theory of Optimization and Continuous Algorithms"
permalink: /teaching/cse535-spring21/
author_profile: false
---

# CSE 535: Theory of Optimization and Continuous Algorithms

The design of algorithms is traditionally a discrete endeavor. However, many advances have come from a continuous viewpoint. Typically, a continuous process, deterministic or randomized is designed (or shown) to have desirable properties, such as approaching an optimal solution or a desired distribution, and an algorithm is derived from this by appropriate discretization. In interesting and general settings, the current fastest methods are a consequence of this perspective. We will discuss several examples of algorithms for high-dimensional optimization, and use them to understand the following concepts in detail.
+ Elimination
+ Reduction
+ Geometrization
+ Sparsification
+ Acceleration
+ Decomposition

## Administrative Information:
+ Lectures: Tue, Thu 10:00-11:20 at	[Zoom](https://washington.zoom.us/j/95120229931)
+ Text Book (in progress): [https://github.com/YinTat/optimizationbook/blob/main/main.pdf](https://github.com/YinTat/optimizationbook/blob/main/main.pdf).
+ Please do not make comment directly on the merged version, but instead the split versions below. Dropbox cannot handle large documents efficiently.
+ Prerequisite: basic knowledge of algorithms, probability, linear algebra.

## Contacts:
+ Instructor: Yin Tat Lee
+ Office Hours: By appointment, email me at (yintat@<span style="display: none;">ignoreme-</span>uw.edu) 
+ TA: Swati Padmanabhan (pswati@<span style="display: none;">ignoreme-</span>cs.washington.edu)
+ TA Office Hours: 1130 am - 1220 am Thu and 930 pm - 1020 pm Thu, zoom link on edstem.
+ Mailing List: [Here](https://mailman.u.washington.edu/mailman/listinfo/cse535a_sp21)
+ Edstem: [Here](https://edstem.org/us/courses/4940)

## Assignments
+ Course evaluation: 5 assignments (100%) or 1 project (100%)
+ Assignments posted and submitted via [Gradescope](https://www.gradescope.com/courses/259020).

## Class Policy
+ You may discuss assignments with others, but you must write down the solutions by yourself.
+ Assignments as well as regrade requests are to be submitted only via gradescope.
+ In general, late submissions are not accepted (the submission server closes at the deadline). Gradescope lets you overwrite previous submissions, so it is recommended to use this feature to avoid missing the submission deadline altogether.
+ We follow the standard [UW CSE policy](https://www.cs.washington.edu/academics/misconduct) for academic integrity.
+ The office hours are for general questions about material from the lecture and homework problems.
+ Please refer to university policies regarding [disability accommodations](http://depts.washington.edu/uwdrs/current-students/accommodations/) or [religious accommodations](https://registrar.washington.edu/staffandfaculty/religious-accommodations-policy/).


## Tentative Schedule:

### Introduction
+ Mar 30: Convexity [Sec 1.1-1.5 (Updated on 31 Mar)](https://www.dropbox.com/s/jp6kftjej0tukrz/lecture%201.pdf)
+ Apr 01: Convexity and Derivative [Sec 4.1-4.4](https://www.dropbox.com/s/o9wn9d6gok0hi95/lecture%202.pdf) [Reading](https://www.dropbox.com/s/wha9wrfs59hco80/reading%202.pdf?dl=0)

### Basic Methods
+ Apr 06: Gradient Descent [Sec 2 (Added Sec 2.6 on 7 Apr)](https://www.dropbox.com/s/cx6husyj2nbfq2e/lecture%203.pdf?dl=0) 
+ Apr 06: (HW 1 due)
+ Apr 08: Gradient Descent (cont) and Proximal Methods (See Sec 2 above)
+ Apr 13: Cutting Plane Methods [Sec 3](https://www.dropbox.com/s/hgtcajmix8q7qzh/lecture%205.pdf?dl=0)
+ Apr 15: Cutting Plane Methods (cont)

### Geometrization
+ Apr 20: Mirror Descent (HW 2 due) [Sec 5](https://www.dropbox.com/s/27jmxsvczvi7v6n/lecture%207.pdf?dl=0)
+ Apr 22: Mirror Descent (cont)

### Homotopy Method
+ Apr 27: Newton Method [Sec 5.3](https://www.dropbox.com/s/6trmy06pmwrrlrw/lecture%209.pdf?dl=0)
+ Apr 29: Interior Point Method [Sec 5.4](https://www.dropbox.com/s/eqwtyvl5tp1lhby/lecture%2010.pdf?dl=0)
+ May 04: Interior Point Method + Cholesky Decomposition [Sec 5.4 rewrite](https://www.dropbox.com/s/b68fq1oxru34fy3/lecture%2011.pdf?dl=0) (HW 3 due or project proposal due)

### Linear System Solving
+ May 06: Leverage Score [Sec 6.2](https://www.dropbox.com/s/gua0gf1rjxfqj7n/lecture%2012.pdf?dl=0)
+ May 11: Laplacian Solver [Sec 8 in Tropp, Matrix Concentration & Computational Linear Algebra](https://hdpa2019.sciencesconf.org/data/pages/Tro19_Matrix_Concentration_LN.pdf)

### Acceleration
+ May 13: Stochastic Gradient Descent & Variance Reduction [Sec 6.3, 6.4](https://www.dropbox.com/s/9c4x09rowvdea7j/lecture%2014.pdf?dl=0)
+ May 18: Accelerated Gradient Descent (HW 4 due) [Sec 7](https://www.dropbox.com/s/brplezbqteg35e3/lecture%2015%202.pdf?dl=0), [Note](https://www.dropbox.com/s/sgdw6cbly3w6g94/lecture%2015.pdf?dl=0)

### Others
+ May 20: Adagrad [Note](https://www.dropbox.com/s/02atdn561ytgy8r/lecture%2016.pdf?dl=0)
+ May 25: Bayesian methods [Note](https://www.dropbox.com/s/fyeuvfxazbunpvo/lecture%2017.pdf?dl=0)
+ May 27: Robust IPM [Note](https://www.dropbox.com/s/8ar4s47o33j65v0/lecture%2018.pdf?dl=0)

### Project Presentations (Depending on Number of Projects)
+ Jun 01: Project
+ Jun 03: Project (HW 5 due)
+ Project report due on Jun 08



## Related Courses:
+ [Aaron Sidford, Introduction to Optimization Theory](https://web.stanford.edu/~sidford/courses/20fa_opt_theory/fa20_opt_theory.html)
+ [Lap Chi Lau, Convexity and Optimization](https://cs.uwaterloo.ca/~lapchi/cs798/index.html)
+ [Nisheeth Vishnoi, Algorithms for Convex Optimization](https://nisheethvishnoi.wordpress.com/convex-optimization/)
+ [Jonathan Kelner, Topics in Theoretical Computer Science: An Algorithmist's Toolkit](http://stellar.mit.edu/S/course/18/sp14/18.409/index.html)
+ [Santosh Vempala, Simple Algorithms](https://algorithms2017.wordpress.com/lectures/)
+ [Sheehan Olver, Numerical Complex Analysis](http://www.maths.usyd.edu.au/u/olver/teaching/NCA/)

## Other Lecture Notes
+ [Sébastien Bubeck, Convex Optimization: Algorithms and Complexity](https://arxiv.org/abs/1405.4980)
+ [Aharon Ben-Tal and Arkadi Nemirovski, Lectures on Modern Convex Optimization](https://www2.isye.gatech.edu/~nemirovs/Lect_ModConvOpt.pdf)
+ [Stephen J. Wright, Optimization Algorithms for Data Analysis](http://www.optimization-online.org/DB_FILE/2016/12/5748.pdf)
+ [Léon Bottou, Frank E. Curtis, Jorge Nocedal. Optimization Methods for Large-Scale Machine Learning](https://arxiv.org/abs/1606.04838)

