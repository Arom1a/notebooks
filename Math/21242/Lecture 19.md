---
date: 2025-10-10
---
## 1 Cauchy-Schwarz Inequality

$$
|angle.l arrow(v), arrow(w) angle.r| <= ||arrow(v)|| dot ||arrow(w)||
$$

## 2 Triangular Inequality

$$
||arrow(v) + arrow(w)|| <= ||arrow(v)|| + ||arrow(w)||
$$

Can be proved using Cauchy-Schwarz Inequality

### 2.1 Triangular Inequality in $CC$

$forall x, y in CC$, we have $|x + y| <= |x| + |y|$, where $|a|$ is the complex modulus. 

$$
|x + y|^2 &= (x + y) overline((x + y)) \
 &= (x + y) (macron(x) + macron(y)) \
&= |x|^2 + |y|^2 + macron(x) y + x macron(y)
$$

$$
(|x| + |y|)^2 &= |x|^2 + |y|^2 + 2|x||y|
$$

$$
dash(x) y + x dash(y) = 2 op("Re")(x dash(y)) <= 2|x dash(y)| = 2|x||y|
$$

$$
therefore |x + y|^2 <= (|x| + |y|)^2
$$

## 3 Parallelogram Identity

$$
||arrow(v) + arrow(w)||^2 + ||arrow(v) + arrow(w)||^2 = 2(||arrow(v)||^2 + ||arrow(w)||^2)
$$

Implication: check if a norm space is an inner product space

## 4 Polarization Identity

$$
"If" arrow(x), arrow(y) in "a real inner product space:" angle.l arrow(x) + arrow(y) angle.r = 1/4 sum_(alpha = plus.minus 1) alpha ||arrow(x) + alpha arrow(y)||^2 \

"If" arrow(x), arrow(y) in "a complex inner product space:" angle.l arrow(x) + arrow(y) angle.r = 1/4 sum_(alpha = plus.minus 1, plus.minus i) alpha ||arrow(x) + alpha arrow(y)||^2 
$$
