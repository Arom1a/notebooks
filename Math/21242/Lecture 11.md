---
date: 2025-09-19
---
Any invertible matrix $A$ can be written as a product of elementary matrices

Computing Inverse

computer the inverse of $\begin{bmatrix}2 & 0 & 1 \\ 1 & 1 & 1 \\ 1 & 0 & 1\end{bmatrix}$

$A \cdot A^{-1} = I$
$G \cdot A = \operatorname{RREF}{(A)} I$
$G = A^{-1}$

$G$ is the sum of elementary matrices?

Let $\vec{v}_{1}, \vec{v}_{2}, \dots, \vec{v}_{k}$ be an independent list of vectors in $V$ with $\operatorname{dim}{(V)} = d$. Then claim: $k \leq d$ and if $k = d$, $\vec{v}_{1}, \vec{v}_{2}, \dots \vec{v}_{k}$ is a basis. 


Lemma: if $\operatorname{dim}{(V)} = d, \exists d < inf$, then any independent list $\vec{v}_{1}, \vec{v}_{2}, \dots, \vec{v}_{k}$ can be extended to a basis. 

> [!proof]+
> We know $k \leq d$
> 
> 1. if $k = d$, we are done
> 
> 2. if $k < d$, we can always find $x$ not in $V \ \operatorname{span}{(\vec{v}_{1}, \vec{v}_{2}, \dots, \vec{v}_{n})}$ to add it into the list to make it a span. 
