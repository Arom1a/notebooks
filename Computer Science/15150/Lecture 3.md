---
date: 2025-09-02
---
## 1 Correctness Proof

- Mathematical induction
- Strong induction
- Structural induction

## 2 Power

### 2.1 Naive Version

```sml
(* power : (int * int) -> int  
REQUIRES: k >= 0  
ENSURES: power(n,k) ==> n^k, with 0^0 = 1. *)
fun power (_ : int, 0 : int) : int = 1
  | power (n, k) = n * power(n, k - 1)
```

### 2.2 Efficient Version

```sml
(* even : int -> bool  
REQUIRES: true  
ENSURES: even(k) evaluates to true if k is even  
evaluates to false if k is odd. *)
fun powere (_ : int, 0 : int) : int = 1
  | powere (n, k) = 
        if even(k) then
            square (powere (n, k div 2))
        else 
            n * powere (n, k - 1)
```

### 2.3 Verification

