---
title: "Computing - Binary"
date: "2020-10-06 10:55"

tags: ["@?computing"]
---

##### What is the binary number $01011011$ in hexadecimal??
$5B$.

##### What is the nibble $0010$ in hexadecimal??
$2$.

##### What is the nibble $1010$ in hexadecimal??
$A$.

##### What is signed binary??
Where the most significant bit indicated whether the number is positive.

##### In signed binary, what does a $1$ sign bit represent??
The number is negative.

##### In signed binary, what does a $0$ sign bit represent??
The number is positive.

##### What is $10010100$ signing bit??
$1$.

##### Is the signed binary number $10010100$ positive or negative??
Negative.

##### What is Two's Complement??
Where the most significant bit is actually the negative value at that position.

##### In Two's Complement binary, what does the 8th bit of an 8 bit binary number represent??
$-128$

##### How can you tell is a Two's Complement binary number is negative??
If the most signifcant bit is set.

##### What is $00010100$ in Two's Complement binary??
$20$

##### What is $11101100$ in Two's Complement binary??
$-20$

##### What are the two ways of representing negative numbers in binary??
* Using signed binary
* Using two's complement

##### What is the most used way of representing negative numbers in binary??
Two's Complement.



##### What are the two ways of representing decimals in binary??
* Fixed point binary

##### What is fixed point binary??
Where the binary number is split into two, with the left hand side being the normal powers of two and the right side being the negative powers of two.

##### What is $2.5$ in an 8-bit fixed point binary number??
$00101000$

##### What is on the left hand side of a fixed point binary number??
The whole powers of two.

##### What is on the right hand side of a fixed point binary number??
The fractional powers of two.

##### If a fixed point binary number has a right-hand side of $1110$, what is the fractional part of the number??
$0.875$.

##### If a fixed point binary number has a right-hand side of $1110$, what is the whole part of the number??
$14$.

##### Write the power row for a 8 bit fixed point binary number??
$8 4 2 1 \frac{1}{2} \frac{1}{4} \frac{1}{8} \frac{1}{16}$

##### Floating point binary is similar to what concept in science??
Standard form.

##### If standard form uses $10^n$, what does floating point binary use??
$2^n$

##### What is the normalised form of $10.1_b$ in floating point binary??
$0.101 \times 2^3$

##### What is the normalised form of $101.1_b$ in floating point binary??
$0.1011 \times 2^3$

##### What is the normalised form of $1110.0010_b$ in floating point inary
$0.1100001 \times 2^4$

##### What is the exponent for a floating point binary number??
The power of two that the normalised fixed point number is raised to.

##### What is the mantissa for a floating point binary number??
The value that is multiplied by the power of two.

##### What do you do to the exponent once you've written a fixed point binary number in normalised form??
Convert it to binary.

##### What's the relationship between fixed-point binary and floating-point binary??
Floating point binary is a normalised fixed-point number (mantissa) being multipled by an exponent.

##### When a normalised floating-point binary number has a one as the first bit, what does it mean??
It's a negative decimal.

##### Is signed binary or two's complement used for a negative mantissa??
Two's complement.

##### What are always the first two bits for a positive floating-point number??
$01$

##### What are always the first two bits for a negative floating-point number??
$10$

##### Why in normalised floating point binary are the first two bits are the same for all positive numbers??
Because if it was $001$ you'd be wasting space, it needs to be $01$ and the exponent increased.

##### What is the effect of increasing the mantissa's bits??
More range.

##### What is the effect of increasing the exponent's bits??
More precision.

##### If the $\frac{1}{2}$ and $\frac{1}{4}$ bits are set in a mantissa and the exponent is $4$, what's the shortcut for working out the decimal representation??
$$
(\frac{1}{2} + \frac{1}{4}) \times 2^4
$$

##### Floating point binary is a combination of what two concepts??
* Fixed point binary
* Standard form

##### What's the first stage for converting a decimal to floating point binary??
Writing the normalised binary representation.

##### If a normalised floating-point number starts with $01$, what does this tell you??
The number is positive.

##### If a normalised floating-point number starts with $10$, what does this tell you??
The number is negative.

##### What is the advantage of floating point binary over fixed point binary??
A much larger range of numbers can be expressed.

##### What's a disadvantage of floating-point binary over fixed point binary??
* Processed slower
* Absolute errors can vary

##### Why are floating point binary numbers processed slower than fixed point ones??
Because the decimal point needs to be moved.

##### When does binary overflow occur??
When the number is too large to be represented by the bits allocated.

##### WHen does binary underflow occur??
When the number is too small to be represented by the bits allocated.

##### What does MSB stand for??
Most significant bit.

##### What does LSB stand for??
Least significant bit.

##### When can underflow occur??
If you add something to a two's complement number.

##### What are the two steps for converting a binary number to two's complement??
* Invert the bits
* Add one

##### A two's compliment number consisting soley of 1s always equals??
$-1$.

##### Why is two's compliment used??
Because arithmetic operations are the same for unsigned binary and two's compliment binary.

##### How do you convert a non-negative two's compliment binary number to unsigned binary??
Just leave it the same.

##### What are the 4 steps for adding floating point numbers together
* Make sure both numbers are normalised
* Make exponenets the same
* Add the mantissas
* Normalise the result

##### What step do you have to remember at the end of adding two floating point numbers together??
Normalising the result.

##### Why does normalised floating point arithmetic work for adding two mantissas together??
Because it's like adding two standard form numbers with the same exponent.

##### What is a truncation error in floating-point arithmetic??
Where some of the less significant bits are missed because there aren't enough bits allocated to the mantissa.

##### If some of the bits can't be represented in a floating-point addition, what is the name of the error??
Truncation Error

##### Float the decimal point of the two's complement number $1.00100_b$ two places to the right??
$$
1.1100100_b
$$

##### Why do you make the smaller exponent match the larger exponent in floating point arithmetic??
Because any truncation error will affect the least significant bits and not the most significant bits.

##### What does the $Ki$ symbol represent??
$$
2^{10}
$$

##### What does the $Ti$ symbol represent??
$$
2^{40}
$$

##### What is the prefix for $2^{30}$??
$$
\text{gibi}
$$

##### What's an example of why a transmission error could occur??
* Electrical interference
* Power surges
* Synchronisation issues
* Wear and tear on the table or connectors

##### What are the 4 main ways to check for errors in transmission??
* Parity bits
* Majority voting
* Check digits
* Checksums

##### What does a parity bit tell you??
Whether the data contains an odd number of zeroes/ones or an even number of zeroes/ones.

##### If you're counting $1$s using a parity bit and using $1$ to represent odd numbers and $0$ to represent even numbers, what is the parity bit for $1001010_b$??
$1$.

##### What are the downsides of parity bits??
* Very rough check
* Don't know which bits are wrong
* If two bits are flipped then it still looks correct

##### What is majority voting for error checking??
Where data is sent multiple times and the data that is recieved the most is treated as correct.

##### If a bit is sent three times with $1 \to 1 \to 0$, what is the value of the bit using majority voting??
$1$

##### What is the downside of majority voting??
Data needs to be sent multiple times which wastes bandwidth.

##### What is a check digit??
A digit calculated from other values which can be used to verify the message sent is correct.

##### Which form of error checking do barcodes use??
Check digits.

##### What's a common way of calculating a check digit??
Using the modulus operation.

##### What is the difference between a check digit and a checksum??
Check sums use a larger amount of data and use more bits to hold the sum.
