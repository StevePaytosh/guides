---
title: Logical Operators
---
## Logical Operators

* **AND**
* **OR**
* **NOT**
* **IF**
* **IFF** (if and only if)
* **XOR** ("exclusive or")

## How They Function
**AND** is only true when both inputs are true. If either input is false, the output will also be false.

| A | B |AND(A,B)|
|---|---|---|
|  f| t | f |
|  f| f | f |
|  t| t | t |
|  t| f | t |

**OR** is true when one or both inputs are true. You'll see in the table below that OR is false only when both inputs are false

| A | B |OR(A,B)|
|---|---|---|
|  f| t | t |
|  f| f | f |
|  t| t | t |
|  t| f | t |

**NOT** is also known as inversion. The output of **NOT** is the opposite of the input. This is the only logical operator that works on only one input, which makes it a unary operator.

| A | B |NOT(A)| NOT(B)
|---|---|---|---|
|  f| t | t |f|
|  f| f | t |t|
|  t| t | f |f|
|  t| f | f |t|

**XOR** is known as **exclusive or** is true when one input or the other is true, but not both. This may seem like a trivial difference from or, but **XOR** is an extremely useful operator.

| A | B |XOR(A,B)|
|---|---|---|
|  f| t | t |
|  f| f | f |
|  t| t | f |
|  t| f | t |




#### More Information:
<!-- Please add any articles you think might be helpful to read before writing the article -->
