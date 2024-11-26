## 1 Big O Notation
Rather than "$f$ is better than $g$", we say $f \in O(g)$: $\exists n_0 \in \mathbb{N}, c\in \mathbb{R} \text{ such that } \forall n \le n_0, f(n) \le c \cdot g(n)$.

It's true that $3n + 2 \in O(n^2)$, but $3n + 2 \in O(n)$ is tighter.

| Complexity Classs | Common Name                   |
| :--------------- | :---------------------------- |
|      $O(1)$       | Constant                      |
|   $O(\log{n})$    | Logarithmic                   |
|      $O(n)$       | Linear                        |
|  $O(n \log{n})$   | just "n log n" or "Loglinear" |
|     $O(n^2)$      | Quadratic                     |
|     $O(2^n)$      | Exponential                   |

## 2 Selection Sort
Find minimum → Put it in the front
