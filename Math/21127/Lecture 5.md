## 1 Principle of Explosion
If a contradiction is assumed, any consequence can be derived. 

## 2 Universal Quantifier
$\forall x \in X, p(x)$ means "for all $x \in X, p(x)$". 

## 3 Universal Quantifier Rules
Introduction rule: if$p(x)$ can be derived from the assumption that $x$ is an arbitrary element of $X$, then $\forall x \in X, p(x)$. 

Elimination rule: if $a \in X$ and $\forall x \in X, p(x)$ is true, then $p(a)$ is true. 

## 4 Existential Quantifier
$\exists x \in X$ means "there exists $x \in X$ such that $p(x)$"> 

## 5 Existential Quantifier Rules
Introduction rule: if $a \in X$ and $p(a)$ is true, then $\exists x \in X, p(x)$. 

Elimination rule: if $\exists x \in X, p(x)$ is true, and $q$ can be derived from the assumption that $p(a)$ is true for some fixed $a \in X$, then $q$ is true. 

## 6 Unique Existential Quantifier
$\exists! x \in X, p(X)$ is shorthand for $$(\underbrace{\exists x \in X,\, p(x)}_{\text{existence}}) ~ \wedge ~ (\underbrace{\forall a \in X,\, \forall b \in X,\, [(p(a) \wedge p(b)) \Rightarrow a=b]}_{\text{uniqueness}})$$

## 7 Quantifier Alternation
$\forall \exists$ statements says weaker than its $\exists \forall$ alternation statements. 

e.g.:
- For every door, there is a key that can unlock it. 
- There is a key that can unlock every door. 

The upper one is weaker than the lower one since we can prove the upper one with the lower one but not the opposite. 

Theorem:
Let $p(x, y)$ be a logical formula with free variables $x \in X$ and $y \in Y$. Then $$\exists y \in Y, \forall x \in X, p(x, y) \Rightarrow \forall x \in X, \exists y \in Y, p(x, y)$$

## 8 Equivalence
$p \equiv q$ means "$p$ can be derived from $q$ and $q$ can be derived from $p$". $(p \equiv q) \Rightarrow (p \Leftrightarrow q)$ but not the opposite. 
e.g.:
I wear a hat iff it is sunny. But "I wear a hat" and "it is sunny" is not logically equivalent. 
