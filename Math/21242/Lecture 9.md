---
date: 2025-09-15
---
## 1 Row Operations:

1. Exchange
2. Scale
3. Replacement

Valid because row operation <$\Rightarrow$ multiplying by an elementary matrix

## 2 Gaussian Elimination

%% 
1. Find left most non-zero column
2. make the first entry of this column 1
3. make all entries below the pivot 0
%%

4. Find left most column with non-zero entry
5. Swap rows so this row is the non-pivot row
6. Multiply row by a non-zero scalar to make this entry 1, call it a pivot
7. By subtracting multiple of this rows

Gaussian Elimination change a matrix to a **row reduction form** (REF),
while Gauss-Jordan Elimination change a matrix to **reduced row echelon form** (RREF)

## 3 Reduced Row Echelon Form (RREF)

1. Each row and column contains at most one pivot. 
Moreover: any pivot in a row $j$ must be strictly be the right of any pivots $i$ s.t. $i < j$. 
Any other entersin a pivot's column must be zero. 

2. All rows after pivot rows are ZERO rows

Need to prove: RREF is unique. 

Theorem: for any $A \in \mathbb{F}^{m \times n}$, there is an invertible matrix $G \in \mathbb{F}^{m \times m}$ s.t. $\operatorname{RREF}{(A}) = G \cdot A$

## 4 Rank of Matrix

The number of pivots in $\operatorname{RREF}{(A)}$

## 5 Pivot and Row, Column

$A \vec{x} = \vec{b}$ has $\leq$ 1 solution for all $\vec{b} \in \mathbb{R}^n$ $\iff$ RREF(A) has pivot in each column $\iff$ $A$ has a left inverse

$A \vec{x} = \vec{b}$ is consistent $\iff$ RREF(A) has pivot in each row $\iff$ $A$ has right inverse
