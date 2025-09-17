---
date: 2025-09-03
---
## 1 Linear Transformation

Suppose $V, W$ are both $\mathbb{F}$ vector spaces, $T : W \to W$ is a linear transformation if 

$\forall \vec{x}, \vec{y} \in V, T(\vec{x} + \vec{y}) = T(\vec{x}) + T(\vec{y})$

$\forall \vec{x} \in V, a \in \mathbb{F}, T(a\vec{x}) = a T(\vec{x})$

Eg1: Consider $\mathbb{F}$ vector spaces $V, W$, find a linear transformation from $V$ to $W$. 

The only one we could find is mapping all vectors in $V$ to $\vec{0}$ in W, i.e. $T(\vec{v}) = \vec{0}$. 

Eg2: Fix $\mathbb{F} = \mathbb{R}$, consider $V = \{a + bx + cx^2 | a, b, c \in \mathbb{R}\}$ with standard operations, $D(f) = f^\prime$ is a linear transformation. 

Theorem: let $V, W$ b $\mathbb{F}$ vector space, and let $B = \vec{v}_{1}, \vec{v}_{2}, \dots \vec{v}_{k}$ be a basis of $V$, and $\vec{w}_{1}, \vec{w}_{2}, \dots, \vec{w}_{k}$ be an arbitrary list of vectors in $W$. There is a unique linear transformation $T = V \to W$ s.t. $\forall i = 1, \dots, k, T(\vec{v})_{i} = \vec{w}_{i}$. 

> [!proof]+
> Existence: Given any $\vec{x} \in V$, consider the unique representation $\vec{x} = \sum\limits_{i = 1}^{k} a_{i} \vec{v}_{i}$, then let $T(\vec{x}) = \sum\limits_{i = 1}^{k} a_{i} \vec{w}_{i}$
>
> Then check the definition of linear transformation for such $T$
> 
> Uniqueness: Suppose $T : V \to W$ and $S : V \to W$, prove that $S(\vec{x}) = T(\vec{x})$

---

> [!draft]-
> Consider a linear transformation $T : \mathbb{F}^m \to \mathbb{F}^n$
> $T$ is uniquely determined by $\{T(\vec{e_{1}}), T(\vec{e}_{2}), \dots, T(\vec{e}_{m})\}$, where $\vec{e}_{1} = \begin{bmatrix} 1 \\ 0 \\ \dots \\ 0\end{bmatrix}, \vec{e}_{2} = \begin{bmatrix} 0 \\ 1 \\ \dots \\ 0\end{bmatrix}, \dots, \vec{e}_{m} = \begin{bmatrix} 0 \\ 0 \\ \dots \\ 1\end{bmatrix}$
