## 1 Logistic Model
$\displaystyle\frac{dP}{dt}=kP(1-\frac{P}{M})\,\Longleftrightarrow\,\frac{dP}{dt}=\frac{k}{M}P(M-P)$

$k$ is maximum growth rate
> However, $(\frac{dP}{dt})_{max}$ is also related to $M$. The maximum is achieved when $P(t)=\frac{1}{2}M$ (the inflection point). The maximum is equals to $\frac{k}{4}M$. It is because $$\frac{dP}{dt}=k\cdot \frac{P}{\sqrt{M}}(\sqrt{M}-\frac{P}{\sqrt{M}})\le k\cdot (\frac{\frac{P}{\sqrt{M}}+\sqrt{M}-\frac{P}{\sqrt{M}}}{2})^2=\frac{k}{4}M$$

$M$ is the carrying capacity
> Which means $$\displaystyle\lim_{t\to \infty}{P(t)}=M (\text{for } k>0)$$ $$\displaystyle\lim_{t\to -\infty}{P(t)}=M (\text{for } k<0)$$