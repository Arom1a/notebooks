## 1 Merge Sort
split into 2 halves → sort 2 halves → merge 2 halves

merge: compare the first in both halves and put the smaller one at the beginning and then compare the first and the second of the selected array

if not allocating a constant array, we say the algorithm is not in-place

Worst: $O(n \log{n})$
Best: $O(n \log{n})$
Average: $O(n\log{n})$

## 2 Proof of Recursive Functions
Don't have loop invariants
INIT: safety of initial call
PRES: preconditions to safety of recursive calls
EXIT: post conditions of recursive calls
TERM:
- base case handles input smaller than some bound
- input is strictly smaller than input of function

## 3 Quick Sort
choose a pivot → smaller than pivot goes left, larger goes right → quick sort on 2 sub arrays partitioned by the pivot

Worst: same as selection sort $O(n^2)$
Best: $O(n \log{n})$
Average: $O(n\log{n})$
