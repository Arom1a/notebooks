## 1 1

Let $arrow(0)_1, arrow(0)_2$ are both additive identities

Then $arrow(0)_2 = arrow(0)_1 + arrow(0)_2 = arrow(0)_1$

## 2 2

$c arrow(0) = c (arrow(0) + arrow(0)) = c arrow(0) + c arrow(0)$

$c arrow(0) + (-c arrow(0)) = c arrow(0) + c arrow(0) + (-c arrow(0))$

$0 = c arrow(0)$

## 3 3

$subset$: sps: $mat(x;y;z) in "span"(mat(1,1,0), mat(0,1,0))$

$supset$: sps: $mat(x;y;z) in {mat(a;b;c) : c = 0}$

## 4 4

suppose not, so there are two solutions $(beta_1, beta_2) != (gamma_1, gamma_2)$.

so 

$$
beta_1 arrow(v)_1 + beta_2 arrow(v)_2 &= 0 \
gamma_1 arrow(v)_1 + gamma_2 arrow(v)_2 &= 0
$$

subtract them

## 5 5

can be true can be false

e.g.: ${mat(1; 0; delim: "["), mat(0; 1; delim: "["), mat(0; 2; delim: "[")}$

## 6 6

for every $arrow(v)$ in $FF^m$, we can find a linear combination

and that linear combination is the .. in the domain

### 6.1 6sub

prove the injective case

## 7 7

### 7.1 $S circle.small T$ is surjective

### 7.2 $S circle.small T$ is not injective

## 8 8

## 9 9

$$mat(1, 0, 0; 0, 1, 0; 0, -5, 1; delim: "[")$$

## 10 10

yes

---

# 0925

## 1 1

(a)

FSOC, assume the columns are dependent. Then, $A arrow(x)$ is the linear combination of $A$ and $arrow(b)$ have more than one solutions. 

(b)

For all vectors in $FF^m$ has at least one way to be written as a linear combination of $A$

(c)

1. the rank of A is n
2. then RREF(A) = G'A for some G' invertible
3. then there are some L that LG'A = I_nxn
4. then LG' is the left inverse

init a rust wasm module, and change the implementation of the decode part using wasm

## 2 2

(1)

## 3 3

suppose this is false. so there exists lists of independent vectors st they don't form a basis

take $L$ to be such list st $L$ is independent, not a basis, and ${} not (L subset.neq L') {}$ for any $L' in {"lists of vectors that cannot be extended)"}$

now let $arrow(w) in V \\ "span"(L)$, then $L union {arrow(w)}$ is independent, not a basis, and its size is larger than $|L|$, contradiction

## 4 4

multiple by invertible matrices

take C an operation
