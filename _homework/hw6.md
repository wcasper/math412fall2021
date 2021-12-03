---
layout: page
title: Homework 6
permalink: /homework/hw6
---

### Directions
Solve the following problems and type up your solutions.  Your solutions should be provided in one of the following formats (in order of preference)
* typed up in $$\LaTeX$$ and submitted as a PDF on Canvas
* written legibly on blank paper, scanned into a PDF and then uploaded on Canvas
* posted on Reddit for fake internet points

If you go with the first strategy, you may wish to check out Overleaf which is a free and intuitive website for generating $$\LaTeX$$ documents online.
If you wish to use the second method and don't own a scanner at home, you can check out the numerous scanning apps available for smartphones.


**Problem 1:**

Show using residue theory that 

$$\int_{-\infty}^\infty \frac{1}{x^4+1}dx = \frac{\pi}{\sqrt{2}}$$

**Problem 2:**

Show using residue theory that

$$\int_0^{2\pi}\frac{1}{a + b\sin\theta} d\theta = \frac{2\pi}{\sqrt{a^2-b^2}}$$

**Problem 3:**

Show using residue theory that

$$\int_{-\pi}^\pi \frac{1-r^2}{1-2r\cos\theta + r^2}\frac{d\theta}{2\pi} = 1,\ \ 0\leq r < 1.$$


**Problem 4:**

For fixed $$m\geq 2$$, show by integrating around the a keyhole (ie. pacman) contour that

$$\int_0^\infty \frac{x^{-a}}{(1+x)^m}dx = \frac{\pi a(a+1)\dots(a+m-2)}{(m-1)!\sin(\pi a)},\ \ 1-m < a< 1.$$ 


**Problem 5:**

How many roots does the polynomial

$$z^9 + z^5 - 8z^3 + 2z + 1$$

have between the circles $$\lvert z\rvert = 1$$ and $$\lvert z\rvert = 2$$?

**Problem 6:**

Let $a\in\mathbb R$.
How many zeros does the polynomial

$$z^4 + z^3 + 4z^2 + az + 3$$

have in the left half of the complex plane? (Your answer will depend on $$a$$).


**Problem 6:**

It turns out that there is a very interesting relationship between the roots of a polynomial $$p(z)$$ and the roots of it's derivative $$p'(z)$$.
Specifically, if plot the roots of $$p(z)$$ as points in the complex plane, then they will form the vertices of a convex polygon, sometimes called the **convex hull** of the roots.  It turns out that the roots of $$p'(z)$$ must lie inside or on the boundary of this polygon!
For example, if $$p(z)$$ is a polynomial whose roots are $$0, i, 1$$ and $$1+i$$, then the roots of $$p'(z)$$ will lie inside the square $$\{x + iy: 0\leq x,y\leq 1\}$$.
We will prove this in this problem.

* (A) Let $$f(z)$$ be a polynomial of degree $$n$$ and let $$a_1,\dots, a_n$$ be the roots of $$f(z)$$.  Prove that if $$z$$ is a root of $$f'(z)$$ which is not a root of $$f(z)$$, then

$$\frac{1}{z-a_1} + \frac{1}{z-a_2} + \dots + \frac{1}{z-a_n} = 0.$$

[Hint: consider the logarithmic derivative of $$f(z)$$]

* (B) Use the formula in part (A) to show that

$$\overline{z}\sum_{j=1}^n\frac{1}{\lvert z-a_j\rvert^2} = \sum_{j=1}^n\frac{\overline a_j}{\lvert z-a_j\rvert^2}$$

* (C) Explain why (B) tells us that $$z$$ lies in the convex hull of $$a_1,\dots, a_n$$.
