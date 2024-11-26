## 1 Search
### 1.1 Linear search
Best: $O(1)$
Avg: $O(n)$
Worst: $O(n)$

### 1.2 Binary search 
Best: $O(1)$
Avg: $O(\log{n})$
Worst: $O(\log{n})$

## 2 Sort
### 2.1 Selection sort
Find the minimum and bring it to the front
Best: $O(n^2)$
Avg: $O(n^2)$
Overall: $O(n^2)$

### 2.2 Merge sort
Recursively Split in halves
Recursively merge halves

Merge: O(n)
Merging $O(\log{n})$
Best: $O(n\log{n})$
Avg: $O(n\log{n})$
Worst: $O(n\log{n})$

### 2.3 Quick sort
Pick pivot
divide smaller and greater based on pivot
Sort

Best: $O(n\log{n})$
Avg: $O(n\log{n})$
Worst: $O(n^2)$

### 2.4 Types of sort
In-place: allocates a constant amount of memory

Stable: relative position of duplicates is preserved

## 3 Pointers and Structs
### 3.1 Local and Allocated memory
Local: literals: int bool string any direct values
die: exit its scope

Allocated: contents of pointers arrays structs
die: no pointers pointed to them (got garbage collected)

int: 0
char: \0

DO NOT DEREFERENCE NULL POINTERS

## 4 Interface vs Implementation
Dev: implements the interface
Client: uses the interface

## 5 Contracts
To prove:
- INITialize
- PREServe
- EXIT
- TERMination
