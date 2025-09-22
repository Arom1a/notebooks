---
date: 2025-09-17
---
For any matrix $A \in \mathbb{F}^{m \times n}$, there is an invertible $G \in \mathbb{F}^{m \times m}$ s.t. $GA = \operatorname{RREF}{(A)}$

## 1 Pivot

$A \vec{x} = \vec{b}$ has $\geq 1$ solutions for all $\vec{b} \in \mathbb{F}^{n}$ $\iff$ $\operatorname{RREF}{(A)}$ has $m$ pivots

## 2 Fundamental Theorems of Linear Algebra

Recall on [[Lecture 8]]

The secret in [[Lecture 8#2 1st Fundamental Theorem of Linear Algebra|1st FTLA]] is: 
injective $\iff$ $\operatorname{Rank}{(A)} = n$

The secret in [[Lecture 8#3 2nd Fundamental Theorem of Linear Algebra|2nd FTLA]] is :
surjective $\iff$ $\operatorname{Rank}{(A)} = m$

The secret in [[Lecture 8#4 3rd Fundamental Theorem of Linear Algebra|3rd FTLA]] is :
bijective $\iff$ $\operatorname{RREF}{(A)} = n = m$

## 3 Every basis have the same size


Theorem: suppose $\vec{v}_{1}, \vec{v}_{2}, \dots, \vec{v}_{n}$ is a basis for $\mathbb{F}^m$, then $k = m$
> [!proof]+
> Apply FTLA3 to the $\begin{bmatrix}\vec{v}_{1} & \vec{v}_{2} & \dots & \vec{v}_{n}\end{bmatrix}$

---

Column vectors corresponding to pivot columns in RREF are independent. 

$\operatorname{Rank}{(AB)} \leq \operatorname{Rank}{(A)}$
