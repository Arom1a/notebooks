## 1 NULL Pointer
Dereferencing a null pointer is a safety issue!

```c0
alloc()
//@ensures \result != NULL

*p
//@ensures p != NULL;
```
