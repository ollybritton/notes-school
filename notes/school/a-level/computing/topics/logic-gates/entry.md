---
title: "Computing - Logic Gates"
date: "2020-09-07 13:54"

tags: ["@?computing"]
---

# Logic Gates
|Name|Shape|
|-|-|
|AND|Like a "D"|
|OR|Like a crescent|
|NOT|Like a triangle with a dot|
|NAND|Like and with a dot|
|NOR|Like an OR with a dot|
|XOR|Like OR with an extra crescent|

#### `AND`
|Input 1|Input 2|Output|
|-|-|-|
|0|0|0|
|0|1|0|
|1|0|0|
|1|1|1|

#### `OR`
|Input 1|Input 2|Output|
|-|-|-|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|1|

#### `NOT`
|Input 1|Output|
|-|-|
|0|1|
|1|0|

#### `NAND`
> AND + NOT

|Input 1|Input 2|Output|
|-|-|-|
|0|0|1|
|0|1|1|
|1|0|1|
|1|1|0|

#### `NOR`
> OR + NOT

|Input 1|Input 2|Output|
|-|-|-|
|0|0|1|
|0|1|0|
|1|0|0|
|1|1|0|

#### `XOR`
> OR, but 1 & 1 is 0.

`XOR` is also sometimes called the `NEQ` operator, meaning "not equivalent". This is because you can also describe it as only being true if the operands differ.

|Input 1|Input 2|Output|
|-|-|-|
|0|0|0|
|0|1|1|
|1|0|1|
|1|1|0|

`XOR` is probably the most popular logical operator in exams. The property that makes this useful is that XOR is like adding two binary numbers together in a single column:

```
| 0|   | 1|   | 1|
| 0|   | 0|   | 1|
|--|   |--|   |--|
| 0|   | 1|   | 0| (1 carried over)
```

##### In terms of the operands, how could you describe XOR??
XOR is true if the operands are different.

##### Why is XOR sometimes called the NEQ operator??
Because it only is true if the operands are different.

##### What property makes XOR useful??
It's like adding two binary digits together in a single column.

##### What is the limitation of XOR as an adder??
It does not deal with carries.

## Half-Adders
A one-bit binary adder. This means it can deal with adding two one-bit binary numbers together and dealing with carries.

They take two inputs:

* __A__, the first binary digit.
* __B__, the second binary digit.

And have two outputs:

* __S__, the sum of the two binary digits.
* __C__, the carry from the addition if there was one.

| A | B | C | S |
| - | - | - | - |
| 0 | 0 | 0 | 0 |
| 0 | 1 | 0 | 1 |
| 1 | 0 | 0 | 1 |
| 1 | 1 | 1 | 0 |

![Half Adder](https://upload.wikimedia.org/wikipedia/commons/thumb/d/d9/Half_Adder.svg/220px-Half_Adder.svg.png)

##### What is a half adder??
A one bit binary adder.

##### How many inputs does a half adder have??
2

##### What inputs does a half adder have??
__A__ and __B__, two binary digits.

##### How many outputs does a half adder have??
2

##### What outputs does a half adder have??
* __S__, the sum of the binary digits.
* __C__, the carry from the sum if there was one.

##### How is a half adder constructed??
PHOTO

##### What is the limitation of a half adder??
Although it outputs a carry, it cannot take a carry as input.

##### What is a half adder that can take a carry as an input called??
A full adder.

##### How many XOR gates does a half adder have??
1

##### How many AND gates does a half adder have??
1

##### How many OR gates does a half adder have??
None!

##### How many NOTs does a half adder have??
None!

## Full Adders
Full adders take three inputs:

* __A__, one bit
* __B__, one bit
* __C in__, a carry bit

They have two outputs:

* __Sum__, the result of adding the two bits and the carry (think "left hand column")
* __C out__, the carry.

| __A__ | __B__ | __C in__ | __C out__ | __Sum__ |
| -     | -     | -        | -         | -       |
| 0     | 0     | 0        | 0         | 0       |
| 0     | 0     | 1        | 0         | 1       |
| 0     | 1     | 0        | 0         | 1       |
| 0     | 1     | 1        | 1         | 0       |
| 1     | 0     | 0        | 0         | 1       |
| 1     | 0     | 1        | 1         | 0       |
| 1     | 1     | 0        | 1         | 0       |
| 1     | 1     | 1        | 1         | 1       |

Notice how the truth table is just like adding three numbers together. You can think of a full adder as a half adder that then has to deal with a carry in bit too. There's this really beautiful way that a full adder is actually just two half adders and an OR gate and it's in my head but I can't get it out.

##### How can you conceptualize a full adder in the context of a half adder??
A full adder is like a half adder that then has to deal with a carry in bit.

##### How is a full adder constructed??
PHOTO

##### How many XOR gates in a full adder??
2

##### How many AND gates in a full adder??
2

##### How many OR gates in a full adder??
1

##### How many NOTs in a full adder??
None!

##### How many inputs does a full adder have??
3

##### How many outputs does a full adder have??
2

##### What are the inputs to a full adder??
* __A__, a binary digit
* __B__, a binary digit
* __C in__, the carry in

##### What outputs does a full adder have??
* __S__, the sum
* __C out__, the carry from the addition if there was one.

##### Why is it important to have a carry in and a carry out in a full adder??
Because adders for multiple bits work as a chain, where the previous carry out is passed on as the carry in.

##### How can you create a multiple bit adder??
* Visualise the multiple bits as two columns, one for each number.
* The first column only needs to be a half-adder because there's no carry in.
* The rest of the columns are full adders, taking the two bits from that column and the previous carry out.

##### In what way is a full adder two half-adders and an OR gate??
* Inputs A and B are run through a half adder, if this overflows then a carry is needed
* The sum of A and B and the carry in are run through a half adder, if this overflows then a carry is needed
