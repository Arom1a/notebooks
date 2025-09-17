---
date: 2025-09-10
---
## 1 Linear Transformations and Matrices

Given $T : U \to V$ with bases $[U]_{B} = A$, $[V]_{B} = B$, we can write the linear transformation as $[T]_{BA}$

Given $A \in \mathbb{F}^{m \times n}$ means $T_{A} = \mathbb{F}^n \to \mathbb{F}^m$

## 2 Inverse of Matrices

Given $T: U \to V$ and $S : V \to U$

We'll say $S$ is a left inverse of $T$ if $S \circ T = id_{U}$, the identity transformation on $U$; we'll say $S$ is a right inverse of $T$ if $T \circ S = id_{V}$, the identity transformation on $V$; we'll say $S$ is a two-sided inverse (or just inverse) if $S$ is both a left and right inverse

Theorem: if $T$ has a left inverse and a right inverse, then the two inverses are both a two-sided inverse, and moreover it is unique

> [!proof]+
> $S_{R} = id_{U} \circ S{R} = S_{L} \circ L \circ S_{R} = S_{L} \circ id_{V} = S_{L}$

## 3 Invertible

When $T$ has a two-sided inverse, we call it $T^{\prime}$ and say $T$ is invertible

Theorem: if $S : U \to V$ is invertible, $T : V \to W$ is invertible, then $T \circ S : U \to W$ is also invertible

## 4 Property of Functions and Invertibility

Theorem: the followings are equivalent

for $A \in \mathbb{F}^{m \times n}$, $T_{a} : \mathbb{F}^n \to \mathbb{F}^m$

1. $T_{A}$ has a left inverse
2. $T_{A}$ is injective
3. The system equation $A \vec{x} = \vec{y}$ has at most one solution $x \in \mathbb{F}^n$ for each $y \in \mathbb{F}^m$
4. The columns of $A$ are linear independent

---

Theorem: let $T : V \to W$, $B = \{\vec{v}_{1}, \vec{v}_{2}, \dots, \vec{v}_{n}\}$ is a basis of $V$, and $C = \{\vec{w}_{1}, \vec{w}_{2}, \dots, \vec{w}_{n}\}$ is a basis of $W$. Then $T(\vec{v}_{1}) = \vec{w}_{1}, T(\vec{v}_{2}), = \vec{w}_{2}, \dots, T(\vec{v}_{n}) = \vec{w}_{n}$, iff $T$ is invertible

> [!proof]+
> TODO

Question: find matrices $A, B$, s.t. $AB$ is invertible but $A$ and $B$ are not

> [!draft]+
> Take $A = \begin{bmatrix}\frac{1}{2} & \frac{1}{2}\end{bmatrix}$, $B = \begin{bmatrix}1 \\ 1\end{bmatrix}$

Theorem: if $AB$ and $A$ are invertible, prove that $B$ is also invertible

> [!proof]+
> lemma: if $A, B$ are both invertible, then $(AB)^{-1} = B^{-1}A^{-1}$

Theorem: if a matrix $A$ is invertible, prove that $A^{\intercal}$ is also invertible

Theorem: if $A$ is a symmetric invertible matrix, then $A^{-1}$ is also symmetric

Theorem: if $AB$ is invertible, then $A$ has a right inverse and $B$ has a left inverse
