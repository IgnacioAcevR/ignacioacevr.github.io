---
title: 'Pseudo-differential Operators'
date: 2026-02-09
permalink: /posts/2026/01/PDO/
tags:
  - cool posts
  - category1
  - category2
---

These are notes from the book *"Pseudo-differential Operators and the Nash-Moser Theorem"* by S. Alinhac and P. Gérard. I have to introduce myself (or remember the memories of the course I took in my M2) into the theory of pseudo-differential operators and semi-classical analysis. For this purpose I found pedagogical and simplified the introduction to this subject given by Alinhac and Gérard.

The first charper present the main elements of the theory of pseudo-differential operators: symbols, operator symbolic calculus, action in Sobolev spaces, and invariance under change of coordinates.

## Introduction

Let $a(\xi)\in \mathcal{C}^\infty$  be a slowly increasing function, we denote $a(D)$ the operator defined on $\mathcal{S}'(\mathbb{R}^n)$ by
\[
\mathcal{F}(a(D)u)(\xi):= a(\xi)\hat{u}(\xi), \qquad \forall u\in\mathcal{S}(\mathbb{R}^n).
\]
The function $a(\xi)$ is called the *symbol of the operator $a(D)$*.

When we compare the formula
\[
(a(D)u)(x) = (2\pi)^{-n}\int e^{ix\xi}a(\xi)\hat u(\xi)d\xi
\]
with the Fourier inversion formula of $u$, it shows that $a(D)$ acts on $u$ only modifying the fragment $e^{ix\xi}\hat u$ of frequency $\xi$ by multiplying its 'amplitude' $\hat u(\xi)$ by $a(\xi)$. Morover,
\[
    \mathcal{F}(a(D)b(D)u)(\xi) = a(\xi)b(\xi)\hat u(\xi).
\]
We can write this like
\[
    a(D)b(D) = (ab)(D).
\]
This is a first example of *"symbolic calculus"*. In this trivial case, $a(D)$ is a p.d.o with constants coefficients, thereby underlying the fact that its symbol does not depend on $x$.

In this chapter, we associate operators $a(x,D)$ with general symbols $a(x, \xi)$ such that the *"amplitude modulating"* nature of the action of $a(x,D)$ emphasized above is preserved, and we obtain symbolic calculus of the type:
\[
    a(x, D)b(x, D) = (a \# b)(x, D),
\]
where $a\#b$ is a certain symbol which we know how to calculate, recovering $ab$ if $b$ has constant coefficients.
