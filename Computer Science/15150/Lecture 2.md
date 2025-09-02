---
date: 2025-08-28
---
## 1 Binding

`[3/x]` means `x` is bound to `3`. 

## 2 Shadowing

Just like Rust lang, sml allows you to bind values to a same variable multiple times, each time assigning the value in the context.

```sml
val x : int = 3;
print ("x in outer scope = " ^ Int.toString x ^ "\n");

let
    val x : string = "Hi, I'm a string now";
in
    print ("x in inner scope = " ^ x ^ "\n");
end;

print ("x in outer scope again = " ^ Int.toString x ^ "\n");
```

## 3 Type Aliases

```sml
type float  real;
type point = float * float;
val p : point = (1.0, 2.6);
```

(creates the binding `[(1.0, 2.6)/p]`)

## 4 Function Declaration

```sml
fun square : (x : int) : int = x * x;
```

now `square` is bound to a **closure**

## 5 Function and Shadowing

```sml
val pi : real = 3.14
fun area (r : real) : real = pi * r * r

area 1.0 (* ==> 3.14 *)
val pi : real = 3.14159
area 1.0 (* ==> 3.14 *)

fun area (r : real) : real = pi * r * r
area 1.0 (* ==> 3.14159 *)
```

## 6 Pattern Matching

```sml
fun fact (n : int) : int =
    if n = 0 then 1 else
    n * fact (n - 1)

fun fact_new (0 : int) : int = 1
  | fact_new n = n * fact (n - 1)
```

```sml
fun fibonacci (n : int) : int =
    if n = 0 then 0 else
    if n = 1 then 1 else
    fibonacci (n - 1) + fibonacci (n - 2)

fun fibonacci_new (0 : int) : int = 0
  | fibonacci_new 1 = 1
  | fibonacci_new n = fibonacci (n - 1) + fibonacci (n - 2)

fun fib_efficient (0 : int) : int * int = (1, 0)
  | fib_efficient 1 = (1, 1)
  | fib_efficient n =
    let
        val (f1 : int, f2 : int) = fib_efficient (n - 1)
    in
        (f1 + f2, f1)
    end
```
