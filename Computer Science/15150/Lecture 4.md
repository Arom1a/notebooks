## 1 Lists

`[v1, ..., vn]`
`[]` or `nil` for empty list

append

## 2 Tail Recursion

```pseudo
func tco (state, accumulator) = 
    if condition then
        tco (state', accumulator')
    else
        (state', accumulator)
```

Tail Call Optimization (TCO) is the functional substitute for loops in imperative languages. 

While imperative languages rely on mutability inside loops, functional language prefers recursion + immutable accumulators, and TCO to ensure the recursion's efficiency. 

## 3 Extensional Equivalence
