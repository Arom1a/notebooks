## 1 Theorem
Let $a, b \in \mathbb{Z}$ with $b \neq 0$. There is exactly one way to write $$a = qb + r$$ such that $q, r \in \mathbb{Z}$, and $0 \leq r < b$ (if $b > 0$) or $0 \leq r < -b$ (if $b < 0$).

## 2 Theorem
Let $a, b, \in \mathbb{C}$. A complex number $\alpha$ is a root of the polynomial $x^2 + ax + b$ if and only if $\alpha = \frac{-a + \sqrt{a^2 - 4b}}{2}$ or $\alpha = \frac{-a - \sqrt{a^2 - 4b}}{2}$

## 3 Theorem
Let $p(x) = a_0 + a_1x + a_2x^2 + \cdots + a_nx^n$ where $a_0, a_1, a_2, ..., a_N \in \mathbb{R}$. If $z \in \mathbb{C}$ is a root of $p$, so is $\bar{z} \in \mathbb{C}$.

## 4 Axiom (Law of excluded middle)
Let $p$ be a propositional formula. Then $p \vee (\neg p)$ is true.

## 5 Axiom (Principle of explosion)
If a contradiction is assumed, any consequence may be derived.

## 6 Theorem
Let $p(x, y)$ be a logical formula with free variables $x \in X$ and $y \in Y$. Then $$\exists y \in Y, \forall x \in X, p(x, y) \Rightarrow \forall x \in X, \exists y \in Y, p(x, y)$$

## 7 Theorem
Two propositional formulae are logically equivalent if and only if their truth values are the same under any assignment of truth values to their constituent propositional variables.

## 8 Theorem (Law of double negation)
Let $p$ be a propositional variable. Then $p \equiv \neg \neg p$.

## 9 Theorem (Law of contraposition)
Let $p$ and $q$ be propositional variables. Then $p \Rightarrow q \equiv (\neg q) \Rightarrow (\neg p)$.

## 10 Theorem (de Morgan's laws for logical operators)
Let $p$ and $q$ be logical formulae. Then:
(a) $\neg(p \wedge q) \equiv (\neg p) \vee (\neg q)$; and
(b) $\neg(p \vee q) \equiv (\neg p) \wedge (\neg q)$.

## 11 Theorem (de Morgan's laws for quantifiers)
Let $p(x)$ be a logical formula with free variable $x$ ranging over a set $X$. Then:
(a) $\neg \forall x \in X, p(x) \equiv \exists x \in X, \neg p(x)$; and
(b) $\neg \exists x \in X, p(x) \equiv \forall x \in X, \neg p(x)$.

## 12 Theorem
Every logical formula (built using only the logical operators and quantifiers we have seen so far) is logically equivalent to a maximally negated logical formula.

## 13 Theorem
Let $p$ and $q$ be logical formulae.
(a) ($q$ can be derived from $p$) iff ($p \Rightarrow q$ is a tautology);
(b) ($p \equiv q$) iff ($p \Leftrightarrow q$ is a tautology).

## 14 Axiom (Set extensionality)
Let $X$ and $Y$ be sets. Then $X = Y$ if and only if $\forall a, (a \in X \Leftrightarrow a \in Y)$, or equivalently, if $X \subseteq Y$ and $Y \subseteq X$.

## 15 Theorem
Let $E$ and $E^\prime$ be sets. If $E$ and $E^\prime$ are empty, then $E = E^\prime$.

## 16 Theorem (de Morgan's law for sets)
(a) $A \setminus (X \cup Y) = (A \setminus X) \cap (A \setminus Y)$; 
(b) $A \setminus (X \cap Y) = (A \setminus X) \cup (A \setminus Y)$; 
(c) $\displaystyle A \setminus \bigcup_{i \in I}{X_i} = \bigcap_{i \in I}(A \setminus X_i)$; 
(d) $\displaystyle A \setminus \bigcap_{i \in I}{X_i} = \bigcup_{i \in I}(A \setminus X_i)$. 

## 17 Axiom (Function extensionality)
Let $f: X \rightarrow Y$ and  $g : A \rightarrow B$ be functions. Then $f = g$ iff the following conditions hold:
(i) $X = A$ and $Y = B$; and 
(ii) $f(x) = g(x)$ for all $x \in X$. 

## 18 Theorem
Let $X$ and $Y$ be sets. A subset $G \subseteq X \times Y$ is the graph of a function iff $$\forall x \in X, \exists! y \in Y, (x, y) \in G$$

## 19 Theorem
Let $X$ be a set and let $U, V \subseteq X$. Then $U = V$ iff $\chi_U = \chi_V$. 

## 20 Theorem
Let $X$ be a set and let $U, V \subseteq X$. Then
(a) $\chi_{U \cap V}(a) = \chi_U(a)\chi_V(a)$ for all $a \in X$;
(b) $\chi_{U cup V}(a) = \chi_U(a) + \chi_V(a) - \chi_U(a)\chi_V(a)$ for all $a \in X$;
(c) $\chi_{X \setminus U}(a) = 1 - \chi_U(a)$ for all $a \in X$. 

## 21 Axiom (Axiom of choice)
Let $\{X_i \mid i \in I\}$ be a family of inhabited sets. Then there is a function $\displaystyle h: I \rightarrow \bigcup_{i \in I}{X_i}$ such that $h(i) \in X_i$ for each $i \in I$. 

## 22 Theorem (Recursion theorem)
Let $X$ be a set. For all $a \in X$ and all $h : \mathbb{N} \times X \rightarrow X$, there is a unique function $f : \mathbb{N} \rightarrow X$ such that $f(0) = a$ and $f(s(n)) = h(n, f(n))$ for all $n \in \mathbb{N}$. 

## 23 Theorem (Weak induction principle)
Let $p(n)$ be logical formula with free variable $n \in \mathbb{N}$, and let $n_0 \in \mathbb{N}$. If 
(i) $p(n_0)$ is true; and 
(ii) For all $n \ge n_0$, if $p(n)$ is true, then $p(N + 1)$ is true;
then $p(n)$ is true for all $n \ge n_0$. 

## 24 Theorem
Let $n, k \in \mathbb{N}$. Then
$$\binom{n}{0} = \begin{cases}\frac{n!}{k!(n - k)!} & \text{if } k \le n \\ 0 & \text{if } k > n \end{cases}$$

## 25 Theorem (Binomial theorem)
Let $n \in \mathbb{N}$ and $x, y \in \mathbb{R}$. Then $$(x + y)^n = \sum_{k = 0}^n{\binom{n}{k}x^ky^{n - k}}$$

## 26 Theorem (Strong induction principle)
Let $p(n)$ be a logical formula with free variable $n \in \mathbb{N}$ and let $n_0 < n_1 \in \mathbb{N}$. If
(i) $p(n_0), p(n_0 + 1), \dots, p(n_1)$ is true; and 
(ii) For all $n \ge n_1$, if $p()$ is true for all $n_0 \le k \le n$, then $p(n + 1)$ is true;
then $p(n)$ is true for all $n \ge n_0$. 

## 27 Theorem (Well-ordering principle)
Let $X$ be a set of natural numbers. If $X$ is inhabited, then $X$ has a least element. 

## 28 Theorem (6.1.7)
Let $m, n \in \mathbb{N}$. 
(a) If there exists and injection $f : [m] \rightarrow [n]$, then $m \le n$. 
(b) If there exists and surjection $g : [m] \rightarrow [n]$, then $m \ge n$. 
(c) If there exists and bijection $h : [m] \rightarrow [n]$, then $m = n$. 

## 29 Theorem (Uniqueness of size)
Let $X$ be a finite set and let $f : [m] \rightarrow X$ and $g : [n] \rightarrow X$ be enumerations of $X$, where $m, n \in \mathbb{N}$. Then $m = n$. 

## 30 Theorem (6.1.14)
Let $X$ and $Y$ be sets. 
(a) If $Y$ is finite and there is an injection $f : X \rightarrow Y$, then $X$ is finite and $|X| \le |Y|$. 
(b) If $X$ is finite and there is an surjection $f : X \rightarrow Y$, then $Y$ is finite and $|X| \ge |Y|$. 
(a) If one of $X$ or $Y$ is finite and there is an bijection $f : X \rightarrow Y$, then $X$ and $Y$ are both finite and $|X| = |Y|$. 

## 31 Theorem (6.1.25)
The set $\mathbb{N}$ is infinite. 
## 32 Important Definitions
**structure proofs** by:
- direct proof: combining axioms, definitions, and earlier theorems
- contraposition: to prove $p \Rightarrow q$, assume $q$ is false and derive $p$ is false
- contradiction: to prove $p$ is true / false, assume $p$ is false / true and derive a contradiction (corresponding)
- exhaustion: to prove $p \Rightarrow q$, split $p$ into multiple cases and derive $q$ in each case
- biconditional proofs: to prove $p \Leftrightarrow q$, assume $p$ prove $q$ and assume $q$ prove $p$

**proposition**: a statement that is able to assign a truth value (paradoxes are not propositions)
**propositional variable**: symbols to represent propositions
**propositional formula**: a propositional variable or an expressions built up from subformulae using a logical operator
**conjunction**: logical "and" operator ($\wedge \text{I}$, $\wedge \text{E}_1$, $\wedge \text{E}_2$)
**disjunction**: logical "or" operator ($\vee \text{I}_1$, $\vee \text{I}_2$, $\vee \text{E}$)
%% **exclusive disjunction**: $\oplus$ %%
**negation**: logical "not" operator ($\neg \text{I}$, $\neg \text{E}$)
**contradiction**: a proposition known or assumed to be false
**implication**: "if ... then ..." ($\Rightarrow \text{I}$, $\Rightarrow \text{E}$)
**biconditional**: $\Leftrightarrow$ "... if and only if ..."

---

**free & bound**:
**predicate**:
**logical formula**: an expression built from predicates using logical operators and quantifiers
**universal quantifier**: \\forall ($\forall \text{I}$, $\forall \text{E}$)
**existential quantifier**: \\exists ($\exists \text{I}$, $\exists \text{E}$)
**unique existential quantifier**: shorthand of existence and uniqueness
**quantifier alternation**:

---

**logically equivalent**:
**tautology**: always true no matter what truth value assigned to components (propositional variables and predicates)

**contrapositive**: reverse and neg both side
**maximally negated**: if the only instance of the $\neg$ appear immediately before a predicate

---

**universal set**: $\mathcal{U}$
**subset & proper subset**:
**inhabited & empty**:
**empty set (null set)**: $\varnothing$
**power set**: $\mathcal{P}(A)$ the set of all the subset of A
pairwise intersection & union: 
disjoint: $X \cap Y$ is empty
indexed intersection & union: 
relative complement:
pairwise cartesian product, ordered pairs: 
n-fold cartesian product:
symmetric difference:
open:

---

function, value, domain (source), codomain (target):
function: set X map (domain / source) to set Y (codomain / target) that each x maps to one unique element $f(x)$ (value) in y. $f : X \to Y$. **Totality**, **Existence**, **Uniqueness**.
graph: the subset of the cartesian product of the domain and the codomain
identity function: $\mathrm{id}_X(x) = x$ for all x in X
empty function: unique! function $\varnothing \rightarrow X$
composite: $\circ$ "first is written last"
characteristic function: $\chi_U(a) = \begin{cases}1 & \text{if } a \in U \\ 0 & \text{if } a \notin U\end{cases}$
image, image under, preimage:


---

injection (one-to-one): only one in domain mapped to one in codomain $\forall a, b \in X, f(a) = f(b) \Rightarrow a = b$
surjective (onto): all codomain mapped $\forall y \in Y, \exists x \in X, f(x) = y$
bijective: in and sur jective
left inverse (post-inverse): $g : Y \rightarrow X$ is a left inverse for $f : X \rightarrow Y$ if $g \circ f = \mathrm{id}_X$
right inverse (pre-inverse): $g : Y \rightarrow X$ is a right inverse for $f : X \rightarrow Y$ if $f \circ g = \mathrm{id}_Y$
two-sided inverse: g is both a left inverse and a right inverse

Even function: $f(-x) = f(x)$
Odd function: $f(-x) = -f(x)$

---

Notion of natural, zero element, successor function, **Peano's axioms**
Summation, Product, Factorial, Binomial coefficient

---

$[n]$: all natural number greater or equals to 1 and less or equals to n
finite set: if there exists a bijection $f : [n] \rightarrow X$ for some $n \in \mathbb{N}$
enumeration: such $f$ is an enumeration of $X$
infinite set: not finite
size (cardinality) of set: $|X|$, unique natural number $n$ such that $[n] \rightarrow X$ is a bijection
