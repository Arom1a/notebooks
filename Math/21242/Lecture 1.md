---
date: 2025-08-25
---
> [!draft]-
> Review Questions
> 
> 1. There are infinite many prime numbers:
> <https://web.math.ucsb.edu/~helena/teaching/math8/handouts/primes.pdf>
> > [!proof]+
> > Suppose there are a finite number of prime numbers and the largest prime number is $p_{k}$, where $k \in \mathbb{Z}$
> > 
> > 

## 1 Field

0. Closed under $+$ and $*$
1. Commutativity: $\forall{a, b} \in \mathbb{F}, a + b = b + a, a * b = b * a$
2. Associativity: $\forall{a, b, c} \in \mathbb{F}, a + (b + c) = (a + b) + c$
3. Identity: $\exists{0, 1} \in \mathbb{F}, s.t. \forall{a} \in \mathbb{F}, a + 0 = a, a * 1 = a$
4. Inverse: $\forall{a} \in \mathbb{F}, \exists{b} \in \mathbb{F}, s.t. a + b = 0$,
$\forall{a} \in \mathbb{F} / {0}, \exists{b} \in \mathbb{f} \text{ s.t. } a * b = 1, \text{ write } a^{-1} \text{ for such } b$
5. Distributivity: 

## 2 Vector Space

A vector space $V$ satisfies:

0. closed under $+$ (vector addition, $f: V \times V \to V$) and $*$ (scalar multiplication, $f: \mathbb{F} \times V \to V$)
1. Commutativity: $\forall \vec{v}, \vec{w} \in V, \vec{v} + \vec{w} = \vec{w} +\vec{v}$. 
2. Associativity: $\forall \vec{u}, \vec{v}, \vec{w} \in V, (\vec{u} + \vec{v}) + \vec{w} = \vec{u} + (\vec{v} + \vec{w})$. 
3. Identity (Additive): $\exists \vec{0} \in V, \text{ s.t. } \forall \vec{v} \in V, \vec{v} + \vec{0} = \vec{v}$. 
4. Inverse (Additive): $\forall \vec{v} \in V, \exists \vec{w} \in V, \text{ s.t. } \vec{v} + \vec{w} = \vec{0} \text{. We denote such additive inverse as } -\vec{v}$. 
5. Identity (Multiplicative): $\forall \vec{v} \in V, 1 \cdot \vec{v} = \vec{v}$. 
6. Associativity (Multiplicative): $\forall \vec{v} \in V \text{ and } \forall \alpha, \beta \in \mathbb{F}, (\alpha\beta)\vec{v} = \alpha(\beta \vec{v})$. 
7. Distributivity I: $\forall \vec{u}, \vec{v} \in V \text{ and } \forall \alpha \in \mathbb{F}, \alpha(\vec{u} + \vec{v}) = \alpha \vec{u} + \alpha \vec{v}$. 
8. Distributivity II: $\forall \vec{v} \in V \text{ and } \forall \alpha, \beta \in \mathbb{F}, (\alpha + \beta)\vec{v} = \alpha \vec{v} + \beta  \vec{v}$. 

## 3 $n$-Dimension Space

$$
\mathbb{R}^{n} = \Bigg\{\begin{pmatrix}
r_{1}  \\
r_{2} \\
\dots \\
r_{n}
\end{pmatrix} | r_{1}, r_{2}, \dots, r_{n} \in \mathbb{R}
\Bigg\}
$$

---

# Recitation

## 1 Prove that $\forall \vec{v} \in V, 0 \vec{v} = \vec{0}$. 

> [!proof]+
> $$
> 0 \vec{v} = (0 + 0) \vec{v} = 0 \vec{v} + 0 \vec{v}
> $$
> 
> $$\therefore 0 \vec{v} = \vec{0}$$