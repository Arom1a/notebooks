---
date: 2025-08-29
---
> [!draft]-
> Review: 
> Theorem: For any list $Y$ in $V$, $Y$ contains a sublist $Y^{'}$, s.t.
> 1. $\operatorname{span}{(Y^{'})} = \operatorname{span}{(Y)}$, and
> 2. $Y^{'}$ is independent
> 
> > [!proof]+
> > Strategy: pick a special sublist, and use contradiction to prove that it is independent
> > 
> > Let $Y^{'}$ be a smallest sublist of $Y$ whose span is $\operatorname{span}{Y}$
> > 
> > Claim: $y^{'}$ is independent

## 1 Basis

$$
\begin{align}
&\text{Let } V \text{ be a vector space, } B = \vec{v_{1}}, \vec{v_{2}}, \dots, \vec{v_{k}} \text{ is a basis of } V  \text{ if: } \\
&\bullet \operatorname{span}{(B)} = V \text{ (Generating)} \\
&\bullet B \text{ is linearly independent}
\end{align}
$$

Theorem:
$$
\forall \vec{u}, \vec{v} \in V_{1}, [\vec{u} + \vec{w}]_{B} = [\vec{u}]_{B} + [\vec{w}]_{B}
$$
$$
\forall c \in \mathbf{F}, \vec{u} \in V, [c \cdot \vec{u}]_{B} = v \cdot [\vec{u}]_{B}
$$

To prove a basis:
Exp. 1: $1, x, x^{2}$ is a basis for polynomial over $\mathbb{R}$ of deg $\leq 2$

> [!proof]+
> Given $p(x) = a + bx + cx^{2} \in V$ we can write $p(x) = a \cdot 1 + b \cdot x + c \cdot x^{2}$
> 
> Moreover, sppose $p(x) = a + bx + cx^{2}$ satisfies $p(x) = A \cdot 1 + B \cdot x + C \cdot x^{2}$
> 
> Then, $A = a, B = b, C = c$

Exp. 2: $1, 1 + x, 1 + x + x^{2}$ is a basis for polynomials over $\mathbb{R}$ of deg $\leq 2$

> [!proof]+
> Generating:
> $1 \in \operatorname{span}{(Y_{2})}$
> 
> $x = 1 + x - 1$, thus $x \in \operatorname{span}{(Y_{2})}$
> 
> $x^{2} = 1 + x + x^{2}$, thus $x^{2} \in \operatorname{span}{(Y_{2}})$
> 
> By lemma $V = \operatorname{span}{(Y_{1})} \subseteq \operatorname{span}{Y_{2}} \subseteq V$, $\operatorname{span}{(Y_{2})} = V$
> 
> Independency:
> Suppose $0 = a \cdot 1 + b \cdot (1 + x) + c \cdot (1 + x + x^{2})$
> 
> $0 + 0x + 0x^{2} = (a + b + c) \cdot 1 + (b + c) \cdot x + c \cdot x^{2}$
> 
> $\implies c = 0$
> 
> and $b + c = 0 \implies b = 0$
> 
> and $a + b + c = 0 \implies a = 0$
