date: 250826


## 1 Imperative vs Functional

|              Imperative              |                Functional                |
| :----------------------------------: | :--------------------------------------: |
|        command being executed        |      expression being evaluated<br>      |
|               `x := 5`               |                 `3 + 5`                  |
| has an effect (creating a new state) | has no side effect (reating a new value) |

## 2 Cost analysis

Work:
- sequential computation
- total sequential time; number of operations

Span:
- Parallel computation
- How long it would take if one could have as many processor s as one wnats; length of longest critical path

## 3 Types

An expression is **well-typed** if it has at least one type, and **ill-typed** otherwise

A well-typed expression may have a value, or may have an effect

For every well-formed ML expression `e`:
- has type `t`, written as `e : t`
- may have a value, written as `e ==> v`

Types:
`int`, `real`, `bool`, `char`, `string`
product types
function types
user-defined types


## 4 Integers, Expressions

`int`:
`..., ~2, ~1, 0, 1, 2, ...`

`e : t`: `e` has type `t`
`e ==> e'`: e reduces to `e'`
`e ↪ e'`: e evaluated to `e'`

## 5 Extensional Equivalence

expressions of type `int` are `≅` if they:
- both evaluate to the same value
- both loop forever
- both raise the same exception

## 6 Products

`(e1, e2)`: `e1` * `e2`

## 7 Declaration

`val pi : real = 3.14`
keyword identifier : type = value