---
title: "Further Maths - Complex Numbers"
date: "2020-09-03 18:02"

tags: ["@?further-maths", "@?public", "@?complex-numbers"]
---

> A complex number is a number with both a real and imaginary part.

### Introducing $i$
First, a couple of definitions:

* Squaring a number is when you multiply it by itself.
* A square root of a number is whatever number squared gives the original number.

$$
\sqrt{25} = \pm 5
\sqrt{1} = \pm 1
$$

But now, what does $\sqrt{-1}$ equal?

$$
\sqrt{-1} = i
$$

This definition means that:

$$
i \times i = -1
-i \times -i = -1
$$

Therefore:

$$
(i)^3 = -i
(i)^4 = 1
(i)^5 = i
$$

As you can see, this sequence repeats every 4 powers. You can find the square roots of other numbers by splitting the square root up and just using algebra:

$$
\sqrt{-25} = \sqrt{25 \times -1} = \sqrt{25} \times \sqrt{-1}
$$

##### What is the definition of $i$?
$i$ is the number where:
* $i^2 = -1
* $$\sqrt{-1} = i$

#### How often does the series $i^n$ repeat??
Every 4 terms.

##### What is $i^3$??
$-i$

##### What is $i^{75}$??
$-i$.

##### What is the solution to $z^2 + 121 = 0$??
$$
11i
$$

### Complex Numbers
Complex numbers are numbers involving $i$ and a "real" number. For example:

$$
3 + 4i
8 - 2i
-6 + 5i
$$

They are written in the form $a+bi$.

##### What is the set of complex numbers called??
$\mathbb{C}$

##### What does $\mathbb{C}$ represent??
The set of all complex numbers.

##### What is the real part of a complex number called??
$\Re(z)$

##### What is the imaginary part of a complex number called??
$\Im(z)$

##### Q: What is $(5+i)(3+4i)$??
$$
11 + 23i
$$

##### Q: What is $(6+3i)(7+2i)$??
$$
36 + 33i
$$

### Conjugates
See [[Further Maths - Conjugates]].

### The Quadratic Formula
At GCSE, the quadratic formula basically had three outcomes depending on the result of $\sqrt{b^2 - 4ac}$:

* A surd, meaning you can't factorise the quadratic
* A square number, meaning that you could factorise.
* Zero, meaning there was only one solution.
* Negative number under the square root, here be dragons.

But at A-Level, we _can_ solve for negative answers using our new friend $i$. Solutions to quadratic equations for complex numbers always come in pairs or conjugates.

### An Example
Conider the cubic:

$$
z^3 + 9z^2 + 33z + 25
$$

Long story short, we get this:

$$
(z+1)(z^2 + 8z + 25)
$$

To find the solutions for $z^2 + 8z + 25$, we can use completing the square:

$$
z^2 + 8z + 25 = 0
(z + 4)^2 - 16 + 25 = 0
(z + 4)^2 + 9 = 0
(z + 4)^2 = -9
(z + 4)^2 = \pm\sqrt{-9}
(z + 4)^2 = \pm3i
z = -4 \pm 3i
$$

So the solutions are:

$$
-4 + 3i
-4 - 3i
$$

Notice how they're a conjugate pair. This leaves us with a final "factorised quadratic" of:

$$
(z + 1)(z - (-4 + 3i))(z - (-4 - 3i))
$$

##### How can you write the brackets for a quadratic with complex solutions $\alpha$ and $\beta$??
$(z - \alpha)(z - \beta)$

##### How can you write the brackets for a quadratic with a complex root of $(a+bi)$??
* $(z - (a+bi))(z - (a-bi))$
* $(z - a - bi)(z - a + bi)$
* $((z-a)+bi)((z-a)-bi)$ - useful for expanding

##### What's a useful way of writing a quadratic with complex solutions for bracket expansion??
* $((z-a)+bi)((z-a)-bi)$
* Grouping real terms together

##### What is interesting about complex roots of a quadratic??
* Complex solutions come in pairs
* If a quadratic has one complex root, the other root will be its complex conjugate.

##### What letters are commonly used for complex solutions of polynomials??
$\alpha$ (alpha), $\beta$ (beta), $\gamma$ (gamma)

##### What other solution does a polynomial have if it has one complex root??
* Complex solutions come in pairs
* If it has one complex root, another root will be its complex conjugate.

### Expanding Brackets with Complex Numbers
There are three main ways:

1. The long, boring way: Multiplying everything out manually.
2. The slightly less boring way: Treating the conjugates themselves as a term and keeping them grouped together.
3. Cool kids only route: Treating something like $(z - (-4 + 3i))$ as $((z + 4) - 3i)$

### Dividing Complex Numbers
Consider something like:

$$
\frac{5+4i}{2-3i}
$$

At first, this might look completely non-sensical. There's not really a way to think about it in this form that makes intuitive sense. However, something like:

$$
\frac{5+4i}{2}
$$

Makes complete sense, you can just do $\frac{5}{2} + 2i$ because the $2$ divides both the $5$ and the $4$. So in order to divide a complex number, we convert the denominator of the fraction into a real number by exploiting the fact that a complex number $z$ multiplied by its conjugate $z^{\ast}$ is a real number (see [[Further Maths - Conjugates]] for a reason why).

In order to solve the $\frac{5+4i}{2-3i}$, we multiply both the top and bottom by the conjugate of the denominator.

$$
\frac{(5+4i) \times (2+3i)}{(2-3i) \times (2+3i)} = \frac{-2 + 23i}{13}
$$

That's much more manageable. We can then just divide through to get a final solution of:

$$
-\frac{2}{13} + \frac{23}{13}i
$$

##### Q: What is $\frac{3-5i}{1+3i}$ in the form $a+bi$??
* Multiply top and bottom by $1 - 3i$.
* $(3-5i)(1-3i) = -12 - 14i$
* $(1+3i)(1-3i) = 1^2 + 3^2 = 10$

$$
\frac{-12 - 14i}{10} = -\frac{6}{5} - \frac{7}{5}i
$$

##### Q: What is $\frac{3+5i}{6-8i}$ in the form $a+bi$??
* Multiply top and bottom by $6+8i$
* $(3+5i)(6+8i) = -22 + 54i$
* $(6-8i)(6+8i) = 6^2 + 8^2 = 100$

$$
\frac{-22 + 54i}{100} = -\frac{11}{50} + \frac{27}{50}
$$

### Polar Form
See [[Further Maths - Polar Form]].

### Argand Diagrams
See [[Further Maths - Argand Diagrams]].
