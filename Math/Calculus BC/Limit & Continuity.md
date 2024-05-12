## 1 How to understand limit
$\lim\limits_{x\to c}=L$ means **The limit as $x$ approaches $c$ of $f(x)$ is equal to the number $L$**

The value of $f(x)$ can be made as close as we please to $L$, for $x$ sufficiently close to $c$, but not equal to $c$.

## 2 What is continuity
To say the function $f(x)$ is continuous at $x=c$, it has to satisfy:
1. $f(c)$ is defined
2. $\lim\limits_{x\to c}{f(x)}$ exists
3. $\lim\limits_{x\to c}{f(x)}=f(c)$

There are three cases of discontinuous:
1. removable discontinuity
![[removable_discontinuity.png]]
2. jump discontinuity
![[jump_discontinuity.png]]
3. infinity discontinuity
![[infinity_discontinuity.png]]

## 3 The Intermediate Value Theorem
If $f$ is a continuous function whose domain contains the interval $[a,b]$, them it takes on any given value between $f(a)$ and $f(b)$ at some point within the interval.

## 4 The Squeeze Theorem
If $f(x)\leq g(x)\leq h(x)$ for all number, and at some point $x=k$ we have $f(x)=h(x)$, then $\lim{g(x)}$ must also be equal to them.
![[squeeze_theorem.png]]