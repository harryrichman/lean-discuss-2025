---
layout: page
title: About
description: >-
    Course policies and information.
math: mathjax
---

# About
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What will we cover?

### Lean demo

From Patrick Massot, [Glimpse of Lean](https://github.com/harryrichman/glimpse-of-lean).

### How to use Lean

  - in the browser, https://live.lean-lang.org/
  - local installation

## Project ideas



### 1. Newton's theorem on real roots

If $$p(x) = a_0 + a_1 x + a_2 x^2 + \cdots + a_n x^n$$ is a polynomial with positive real coefficients $$a_i > 0$$, and $$p(x)$$ has all (negative) real roots, then the coefficient sequence is *ultra log-concave*, i.e.

$$
2 \log\left(\frac{a_i}{n \choose i}\right) \geq \log\left(\frac{a_{i - 1}}{n \choose {i-1}}\right) + \log\left(\frac{a_{i + 1}}{n \choose {i+1}}\right) \qquad\text{for all $i$}.
$$


### 2. Cauchy interlacing theorem

If $$A$$ is a symmetric matrix with eigenvalues $$\lambda_1 \leq \lambda_2 \leq \cdots \leq \lambda_n$$,
and $$B$$ is obtained from $$A$$ by deleting the last row and column,
then the eigenvalues $$\mu_1 \leq \mu_2 \leq \cdots \leq \mu_{n - 1}$$ of $$B$$ must *interlace* the eigenvalues of $$A$$, i.e. they satisfy

$$
\lambda_i \leq \mu_i \leq \lambda_{i + 1}, \qquad\text{for all $i$}.
$$

### 3. Puiseux's theorem

Let $$k$$ be an algebraically closed field, and let $$k((x))$$ denote the field of Laurent series in the formal variable $$x$$;

$$
k((x)) = \left\{ x^v(a_0 + a_1 x + a_2 x^2 + \cdots) : a_i \in k,\, v \in \mathbb Z \right\}.
$$

Let $$k\{\{x\}\}$$ denote the union of $$k((x^{1/n}))$$ for all positive integers $$n$$; we call $$k\{\{x\}\}$$ the field of *Puiseux series*.
Then, $$k\{\{x\}\}$$ is algebriacally closed.


### 4. Descartes's rule of signs

See [Descartes's rule of signs](https://en.wikipedia.org/wiki/Descartes%27_rule_of_signs).

### 5. Sturm's theorem for polynomial roots

See [Sturm's theorem](https://en.wikipedia.org/wiki/Sturm%27s_theorem).

### 6. Newton's theorem for valued fields

See [Newton polygon - main theorem](https://en.wikipedia.org/wiki/Newton_polygon#Main_theorem).


## Resources

See other page
