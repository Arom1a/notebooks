## 1 Integrals containing trigonometric functions
### 1.1 Only sine & cosine
|   &ensp;    |                           Integral                           |          Used identity           |                                         Method                                         |
|:-----------:|:------------------------------------------------------------:|:--------------------------------:|:--------------------------------------------------------------------------------------:|
| $n$ is odd  |     $\int{\sin^n{x}\,dx}=\int{\sin^{n-1}{x}\sin{x}\,dx}$     |     $\sin^2{x}=1-\cos^2{x}$      |  Use the indentity with the single sine and then uses u-substitution with $u=\cos{x}$  |
|      ^      |     $\int{\cos^n{x}\,dx}=\int{\cos^{n-1}{x}\cos{x}\,dx}$     |     $\cos^2{x}=1-\sin^2{x}$      | Use the indentity with the single cosine and then uses u-substitution with $u=\sin{x}$ |
| $n$ is even | $\int{\sin^n{x}\,dx}=\int{[\frac{1-\cos{2x}}{2}]^{n/2}\,dx}$ | $\sin^2{x}=\frac{1-\cos{2x}}{2}$ |                             Expand the power to calculate                              |
|      ^      | $\int{\cos^n{x}\,dx}=\int{[\frac{1+\cos{2x}}{2}]^{n/2}\,dx}$ | $\cos^2{x}=\frac{1+\cos{2x}}{2}$ |                             Expand the power to calculate                              |
### 1.2 Both sine & cosine
### 1.3 Both secant & tangent
### 1.4 Product-to-sum Identities

## 2 Trigonometric substitution

|             Form             |      Identity       |
| :--------------------------: | :-----------------: |
| $\int{\sqrt{a^2 - x^2}\,dx}$ | $x = a\sin{\theta}$ |
| $\int{\sqrt{a^2 + x^2}\,dx}$ | $x = a\tan{\theta}$ |
| $\int{\sqrt{x^2 - a^2}\,dx}$ | $x = a\sec{\theta}$ |


$\frac{\alpha - \sin(\alpha)}{2* (\beta - \sin(\beta))}$