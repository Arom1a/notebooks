$\int{\cos{x}\,dx}=\sin{x}+c$
$\int{\sin{x}\,dx}=-\cos{x}+c$
$\int{\sec{x}\tan{x}\,dx}=\sec{x}+c$
$\int{\csc{x}\tan{x}\,dx}=-\csc{x}+c$
$\int{\sec^{2}{x}\,dx}=\tan{x}+c$
$\int{\csc^{2}{x}\,dx}=\cot{x}+c$

$\int{\frac{1}{\sqrt{1-x^{2}}}\,dx}=\sin^{-1}{x}+c$
$\int{\frac{1}{1+x^{2}}\,dx}=\tan^{-1}{x}+c$
$\int{\frac{1}{x\sqrt{x^{2}-1}}\,dx}=\cot^{-1}{x}+c$

$\int{x^{a}\,dx}=\frac{x^{a+1}}{a+1}+c$
$\int{x^{-1}\,dx}=\ln{{\left|x\right|}}+c$
$\int{e^{x}\,dx}=e^{x}+c$
$\int{a^{x}\,dx}=\frac{a^{x}}{\ln{a}}+c$

$$\frac{d}{dt}\int^{h(x)}_{g(x)}{f(t)}\,dt=\frac{d}{dt}\int^{h(x)}_{0}{f(t)\,dt}-\frac{d}{dt}\int^{g(x)}_{0}{f'(t)\,dt}=h'(x)\times f(h(x))-g'\times f(g(x))$$

**Integration by substitution (u-Substitution):**
Let $u=g(x)$, then $du=g'(x)\times dx$
$$\int{f\big(g(x)\big)g'(x)\,dx}=\int{f(u)\,du}=F(u)+c$$
**Integration by part:**
$$\int{u\frac{dv}{dx}\,dx}=uv-\int{v\frac{du}{dx}dx}$$
**Partial integration:**
**eg.** To calculate
$$\int{\frac{3x+11}{x^{2}-x-5}\,dx}$$$$=\int{(\frac{4}{x-2}-\frac{1}{x+2})\,dx}=4\ln{\left|x-3\right|}-\ln{\left|x+2\right|}+c$$