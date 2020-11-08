---
title: "Computing - Boolean Algebra"
date: "2020-09-08 10:08"

tags: ["@?computing"]
---

# Boolean Algebra
Boolean algebra is like writing algebraic expressions acting on variables. Boolean _notation_ is the set of symbols that define logical operators on variables.

$$
P = \text{NOT} (A \text{AND} B)
P = \overline{A \cdot B}
$$

$$
P = (A \text{AND} B) \text{OR} C
P = (A \cdot B) + C
$$


### NOT
$$
P = \text{NOT} A
P = \overline{A}
$$

##### What does the notation $\overline{A}$ in boolean algebra??
NOT.

### AND
$$
P = A \text{AND} B
P = A \cdot B
$$

##### What does the notation $A \cdot B$ mean in boolean algebrea??
AND.

### OR
$$
P = A \text{OR} B
P = A + B
$$

##### What does the notation $A + B$ mean in boolean algebra??
OR.

### XOR
$$
P = A \text{XOR} B
P = A \oplus B
$$

##### What does the notation $A \oplus B$ mean in boolean algebra??
XOR.

### NOR and NAND
Instead of having a special notation, you write these as boolean expressions themselves.

$$
P = \text{NOT} (A \text{OR} B)
P = \overline{(A + B)}
$$

##### What is NOR in boolean notation??
$$
\overline{(A+B)}
$$

##### What is NAND in boolean notation??
$$
\overline{(A \cdot B)}
$$

##### What is the order of operations for boolean algebra??
1. Highest: NOT
2. Middle: AND
3. Lowest: OR



### De Morgan's Laws
##### Who was Augustus De Morgan??
August De Morgan was a mathematician who invented laws to simplify boolean expressions.

##### What is De Morgan's first law??
$$
\overline{A} \cdot \overline{B} = \overline{A+B}
$$

##### What is $\overline{A} \cdot \overline{B}$ equivalent to??
$$
\overline{A + B}
$$

#### What is De Morgan's second law??
$$
\overline{A \cdot B} = \overline{A} + \overline{B}
$$

##### What is $\overline{A \cdot B}$ equivalent to??
$$
\overline{A} + \overline{B}
$$

##### In boolean algebra, simplify $X \cdot 0$$??
$0$

##### In boolean algebra, simplify $X \cdot 1$??
$X$

##### In boolean algebra, simplify $X \cdot X$??
$X$

##### In boolean algebra, simplify $X \cdot \overline{X}$??
$0$

##### In boolean algebra, simplify $X + 1$??
$X$

##### In boolean algebra, simplify $X + 1$??
$1$

##### In boolean algebra, simplify $X + X$??
$X$

##### In boolean algebra, simplify $X + \overline{X}$??
$1$

##### In boolean algebra, simplify $\overline{\overline{X}}$??
$X$

##### What is the commutative rule??
The order of operations does not matter.

##### Because of the commutative rule, what is $X \cdot Y$ equivalent to??
$$
Y \cdot X
$$

##### What is the associative rule??
Doing __A__ then __B__ is the same as doing __B__ then __A__.

##### Because of the associative rule, what is $X \cdot (Y \cdot Z)$ equivalent to??
$$
(X \cdot Y) \cdot Z
$$

##### What is the distributive rule??
Applying an operand to a bracket is the same as applying the operand to each term of the bracket.

##### Because of the distributive rule, what is $X \cdot (Y + Z)$ equivalent to??
$$
X \cdot Y  + X \cdot Z
$$

##### In boolean algebra, simplify $(A \cdot \overline{A}) + B$??
$$
B
$$

##### In boolean algebra, simplify $(A \cdot B) + (\overline{A} \cdot B)$??
$$
B
$$

##### In boolean algebra, simplify $A \cdot B + A \cdot (B + C)$??
$$
A \cdot (B + C)
$$
