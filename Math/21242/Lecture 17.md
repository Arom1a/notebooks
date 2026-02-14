---
date: 2025-10-06
---
## 1 Cofactor Matrix

Let $A_(j, k)$ denotes the $(n - 1) times (n - 1)$ cofactor matrix obtained from a ${} n times n {}$ matrix $A$ by deleting out row $j$ and column $k$. 

### 1.1 Cofactor Expansion

$$
A = mat(
    a_(1, 1), a_(1, 2), a_(1, 3), a_(1, 4), ..., a_(1, n);
    a_(2, 1), a_(2, 2), a_(2, 3), a_(2, 4), ..., a_(2, n);
    a_(3, 1), a_(3, 2), a_(3, 3), a_(3, 4), ..., a_(3, n);
    dots.v, dots.v, dots.v, dots.v, dots.v, dots.v;
    a_(n, 1), a_(n, 2), a_(n, 3), a_(n, 4), ..., a_(n, n);
    delim: "["
)
$$

For any row number $j$, we can expand the determinant of $A$ as 
$$
det(A) = sum_(k = 1)^n (-1)^(j + k) a_(j, k) dot det(A_(j, k))
$$

And for any column number $k$, we can also expand the determinant of $A$ as 
$$
det(A) = sum_(j = 1)^n (-1)^(j + k) a_(j, k) dot det(A_(j, k))
$$

We can prove the expansion on row $1$ and generalize it by changing rows. 

$$
#proof[

]
$$
