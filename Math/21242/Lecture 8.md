---
date: 2025-09-12
---
## 1 Kernel and Column Space

Given a linear transformation $T : U \to V$, 

$\operatorname{Ker}{(T}) = \{\vec{u} \in U | T(\vec{u}) = \vec{0}_{V}\}$

$I_{m}(T) = \{\vec{v} \in V | \exists \vec{u} \in U, T(\vec{u}) = \vec{v}\}$

## 2 1st Fundamental Theorem of Linear Algebra

For $A \in \mathbb{F}^{m \times n}$ matrix and so $T_{A} = \mathbb{F}^{n} \to \mathbb{F}^{m}$

1. $T_{A}$ is injective
2. $\forall \vec{y} \in \mathbb{F}^{m}$, the equation $A \vec{x} = \vec{y}$ has $\leq 1$ solution
3. The columns of $A$ are independent
4. $\operatorname{Ker}{(T_{A}}) = \{\vec{0}_{\mathbb{F^{n}}}\}$
5. $T_{A}$ has a left-inverse
6. (Secret)

Moreover: All these imply $m \geq n$

^1st

## 3 2nd Fundamental Theorem of Linear Algebra

For $A \in \mathbb{F}^{m \times n}$ matrix and so $T_{A} = \mathbb{F}^{n} \to \mathbb{F}^{m}$

1. $T_{A}$ is surjective
2. $\forall \vec{y} \in \mathbb{F}^{m}$, exists a solution to $A \vec{x} = \vec{y}$
3. The columns of $A$ span $F^{m}$
4. $\operatorname{I_{m}}{(T_{A}}) = \mathbb{F}^{m}$
5. $T_{A}$ has a right-inverse
6. (Secret)

Moreover: All these imply $m \leq n$

## 4 3rd Fundamental Theorem of Linear Algebra

For $A \in \mathbb{F}^{m \times n}$ matrix and so $T_{A} = \mathbb{F}^{n} \to \mathbb{F}^{m}$

1. $T_{A}$ is bijective
2. $\forall \vec{y} \in \mathbb{F}^{m}$, the equation $A \vec{x} = \vec{y}$ has exactly one solution
3. The columns of $A$ are a basis for $\mathbb{F}^{m}$
4. $\operatorname{Ker}{(T_{A}}) = \{\vec{0}_{\mathbb{F^{n}}}\}$, $I_{m}(T_{A}) = \mathbb{F}^{n}$
5. $T_{A}$ has a two-sided inverse
6. (Secret)

Moreover: All these imply $m = n$

---

Theorem: if $T_{A}$ is bijective, $T_{A}$ has an inverse

> [!proof]+
> Since $T_{A}$ is a bijection, it has an inverse function $f : \mathbb{F}^{m} \to \mathbb{F}^{n}$
> We need to check that $f$ is a linear transformation
> 
> $T_{A}(f(\vec{x} + f(\vec{y}))) = T_{A}(\vec{x}) + T_{A}(\vec{y}) = \vec{x} + \vec{y} = T_{A}(f(\vec{x} + \vec{y}))$
>
> $T_{A}(a f(\vec{x})) = a T_{A}(f(\vec{x})) = a \vec{x}$

## 5 Gaussian Elimination

Find left most column with a non-zero entry 
