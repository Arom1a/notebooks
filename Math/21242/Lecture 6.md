---
date: 2025-09-08
---
Given $\mathbb{F}$-vector space, $U, V, W$ with basis $\mathcal{A}, B, C$

$S : U \to V, T = V \to W$, $T \circ S$ is a linear transformation $T \circ S : U \to W$

$[T \circ S]_{\mathcal{CA}} = \begin{matrix}| & | &  & |\end{matrix}$

---

Given matrices $A, B$, $A = m \times n$ whose columns are $\vec{a}_{1}, \vec{a}_{2}, \dots, \vec{a}_{n}$, $B = n \times l$ whose columns are $\vec{b}_{1}, \vec{b}_{2}, \dots, \vec{b}_{l}$, The product $A \cdot B$ is the $m \times l$ matrix whose columns are $A \vec{b}_{1}, A \vec{b}_{2}, \dots, A \vec{b}_{l}$. 

E.g.: 
$$
A = \begin{pmatrix}
4 & 2 & 0 & -1 \\
3 & 1 & 0 & 2
\end{pmatrix}, B = \begin{pmatrix}
3 & 2 \\
1 & 1 \\
3 & 2 \\
0  & 0
\end{pmatrix}
$$
$$
AB = \begin{pmatrix}
14 & 10 \\
10 & 7
\end{pmatrix}
$$

---

$\mathbb{F}^{m \times n}$ is a set of $m \times n$ matrices. It has an addition operation: pointwise addition, also scalar multiplication: $\mathbb{F}^{m \times n}$ is an $\mathbb{F}$-vector space

Theorem: for $\mathbb{F}$-vector spaces $U, V$. The set of linear transformation $T : U \to V$ is an $\mathbb{F}$-vector space. 

---

Matrices have additive inverse

Matrix multiplication is associative: $A(BC) = (AB)C$

Matrix has distributivity: $A(B + C) = AB + AC$


> [!proof]+
> $(T + S)(\vec{x}) = T(\vec{x}) + S(\vec{x})$
> 
> $(\alpha \cdot T)(\vec{x}) = \alpha \cdot T(\vec{x})$
> 
> $T$ has additive inverse $T^{\prime}$, $T^{\prime}(\vec{x}) = -T(\vec{x})$
> 
> $A \in \mathbb{F}^{m \times x}, B \in \mathbb{F}^{n \times l}, C = \mathbb{F}^{l \times k}$
> Associativity: $(AB)C = A(BC)$
> > [!proof]+
> > Given $A \in \mathbb{F}^{m \times n}$, let $T_{A} : \mathbb{F}^{n} \to \mathbb{F}^{m}$ given by $T_{A}(\vec{x}) = A \vec{x}$
> > 
> > $T_{AB} T_{C} = T_{A} \circ T_{B} \circ T_{C} = T_{A} T_{BC}$

