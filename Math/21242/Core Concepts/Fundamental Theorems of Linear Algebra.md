Let $A$ be an $m times n$ matrix, and $T_A : FF^n -> FF^m$ be the transformation $arrow(x) -> A arrow(x)$. 

## 1 1st FTLA

The following are equivalent:

1. $T_A$ is injective
2. For each $arrow(b) in FF^m$, $A arrow(x) = arrow(b)$ has $<=$ 1 solution
3. The columns of $A$ are linearly independent
4. The kernel of $T_A$ has the only element $arrow(0)_(FF^n)$
5. $T_A$ has a left inverse
6. $"rank"(A) = n$

Moreover, these imply ${} n <= m {}$ ($A$ is tall). 

## 2 2nd FTLA

TFAE:

1. $T_A$ is surjective
2. For each $arrow(b) in FF^m$, $A arrow(x) = arrow(b)$ has $>=$ 1 solution
3. The columns of $A$ span $FF^m$
4. The image of $T_A$ is $FF^m$
5. $T_A$ has a right inverse
6. $"rank"(A) = m$

Moreover, these imply $n >= m$ ($A$ is wide). 

## 3 3rd FTLA

TFAE:

1. $T_A$ is bijective
2. For each $arrow(b)$ in $FF^m$, $A arrow(x) = arrow(b)$ has exactly 1 unique solution
3. The columns of $A$ are a basis of $FF^m$
4. The kernel of ${} T_A {}$ has the only element $arrow(0)_(FF^n)$ and the image of $T_A$ is $FF^m$
5. $T_A$ has a two-sided inverse
6. $"rank"(A) = n = m$

Moreover, these imply $n = m$ ($A$ is square). 

TODO: prove
