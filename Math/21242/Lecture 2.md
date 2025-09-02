---
date: 2025-08-27
---
Review:

Theorem: $\text{in an } \mathbb{F} \text{ vector space } V, \forall{\vec{v}} \text{ in } V, 0 * \vec{v} = \vec{0}$

Theorem: $-1 * \vec{v} = -\vec{v}$

---

## 1 Linear Combination

Given a list $\mathbb{L} = \vec{v_1}, \vec{v_2}, ..., \vec{v_k}$, a linear combination of

## 2 Span

$\operatorname{span}{(Y)}$: is a set of vectors $\vec{w}$ that can be represented as linear combinations of $Y$

---

$Y_{1} = \left\{ \begin{bmatrix}1 \\ 0\end{bmatrix}, \begin{bmatrix}0 \\ 1\end{bmatrix} \right\}$

$Y_{2} = \left\{ \begin{bmatrix}0 \\ 0\end{bmatrix}, \begin{bmatrix}1 \\ -1\end{bmatrix}, \begin{bmatrix}-\pi \\ \pi\end{bmatrix} \right\}$

Claim: $\operatorname{span}{(Y_{1})} = R^{2}$

subset: by closure of operation

tesbus: let v = (r1, r2) in R^2 we have r1 * (1, 0) + r2 * (0, 1)* = v

Claim: Span(Y2) = {(r, -r), r in R}

---

## 3 Independence

$Y \text{ is independent if each vector in } \operatorname{span}{(Y)} \text{ has a unique representation as a linear combination of } Y$

Theorem: $Y \text{ is independent} \iff \vec{0} \text{ has only the trivial representation of } \vec{0} = 0 * \vec{v_{1}} + 0 * \vec{v_{2}} + \dots + 0 * \vec{v_{k}}$

Theorem: $Y = \vec{v_{1}}, \vec{v_{2}}, \dots, \vec{v_{k}} \text{ is dependent} \iff \text{exists } j \text{ where } 1 \leq j \leq k \text{ s.t. } \vec{v_{j}} = a_{1} * \vec{v_{1}} + a_{2} * \vec{v_{2}}, + \dots + \vec{v_{j - 1}}$

prop: $\vec{v_{1}}, \vec{v_{2}}, \dots, \vec{v_{k}} \text{ is linearly dependent} \iff \text{one of the vectors can be represented as a linear combination of the rest}$

---

# Recitation

## 1 Find a basis for $3\times 2$ matrices ($M_{3\times2}$)

$$
\left\{
    \begin{bmatrix}
    1 & 0 \\
    0 & 0 \\
    0 & 0
    \end{bmatrix}, 
    \begin{bmatrix}
    0 & 1 \\
    0 & 0 \\
    0 & 0
    \end{bmatrix}, 
    \begin{bmatrix}
    0 & 0 \\
    1 & 0 \\
    0 & 0
    \end{bmatrix}, 
    \begin{bmatrix}
    0 & 0 \\
    0 & 1 \\
    0 & 0
    \end{bmatrix}, 
    \begin{bmatrix}
    0 & 0 \\
    0 & 0 \\
    1 & 0
    \end{bmatrix}, 
    \begin{bmatrix}
    0 & 0 \\
    0 & 0 \\
    0 & 1
    \end{bmatrix} \\
\right\}
$$

## 2 T/F questions

Any set containing $\vec{0}$ is linearly dependent $\rightarrow$ T

A basis must contain $\vec{0}$ $\rightarrow$ F

Subset of linearly dependent sets are linearly dependent $\rightarrow$ F

Subset of linearly independent sets are linearly independent $\rightarrow$ T
## 3 Find a basis for $2 \times 2$ symmetric matrices

($A^\intercal = A$, $\begin{bmatrix}a & b \\ b & c\end{bmatrix}$)

$$
\left\{
    \begin{bmatrix}
        0 & 0 \\
        0 & 1
    \end{bmatrix},
    \begin{bmatrix}
        1 & 0 \\
        0 & 0
    \end{bmatrix}, 
    \begin{bmatrix}
        0 & 1 \\
        1 & 0
    \end{bmatrix}
\right\}
$$

## 4 Is the following possible?

- $\vec{v_1}, \vec{v_2}, \vec{v_3}$ are linearly dependent
- $\vec{w_1} = \vec{v_1} + \vec{v_2}, \vec{w_2} = \vec{v_2} + \vec{v_3}, \vec{w_3} = \vec{v_3} + \vec{v_1}$ are linearly independent
