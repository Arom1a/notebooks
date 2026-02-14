---
date: 20250929
---
## 1 Determinant

Properties of the determinant function:

Given a $2 times 2$ matrix $(arrow(v_1), arrow(v_2))$, we want a function that follows:

1. $f(I_2) = 1$
2. Alternating: $f(arrow(v), arrow(v)) = 0$
3. Multilinearity:
    1. $f(arrow(v) + arrow(w), arrow(c)) = f(arrow(v), arrow(c)) + f(arrow(w) + arrow(c))$
    2. $f(alpha arrow(v), arrow(c)) = alpha f(arrow(v), arrow(c))$

With these properties, we can show $f(arrow(v)_1, arrow(v)_2) = -f(arrow(v)_2, arrow(v)_1)$ (antisymmetric). And following that, $f(mat(a, b; c, d)) = a d - b c$. 

> [!proof]-
> $f(mat(a;c), mat(b;d))) = f(mat(a;0) + mat(0;c), mat(b;0) + mat(0;d))$

If replace alternating with antisymmetric, it doesn't work in $FF_2$
