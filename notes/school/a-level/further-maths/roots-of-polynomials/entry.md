---
title: "Further Maths - Roots of Polynomials"
date: "2020-10-19 20:06"

tags: ["@?further-maths", "@!public"]
---

### Summary
##### In summary, what is the roots of polynomials topic about??
Exploring the underlying relationship between the roots of a polynomial and the coefficient of each term.

### Basic Notations
##### What are the two roots of a quadratic called??
$$
\alpha, \beta
$$

##### What are the three roots of a cubic called??
$$
\alpha, \beta, \gamma
$$

##### What are the four roots of a quartic called??
$$
\alpha, \beta, \gamma, \delta
$$

### Definitions
##### What is the sum of the roots $\alpha + \beta$ equal to for a quadratic??
$$
-\frac{b}{a}
$$

##### What is the product of the roots $\alpha \beta$ equal to for a quadratic??
$$
\frac{c}{a}
$$

##### For a simple quadratic with $x^2$ coefficient $1$, how could you write the quadratic in terms of its roots $\alpha$ and $\beta$??
$$
x^2 - (\alpha + \beta)x + \alpha\beta
$$

##### What does $-\frac{b}{a}$ equal in terms of the roots of a quadratic $\alpha$ and $\beta$??
$$
\alpha + \beta
$$

##### What does $\frac{c}{a}$ equal in terms of the roots of a quadratic $\alpha$ and $\beta$??
$$
\alpha \beta
$$

##### How could you write $\frac{1}{\alpha} + \frac{1}{\beta}$ as a combination of useful $\alpha$ and $\beta$ expressions??
$$
\frac{\alpha + \beta}{\alpha\beta}
$$

##### How could you write $\alpha^2 + \beta^2$ as a combination of useful $\alpha$ and $\beta$ expressions??
$$
(\alpha + \beta)^2 - 2\alpha\beta
$$

##### If you have $6x^2 + 7x - 10$ and you want to find the sum of the roots, what's the first step??
Writing it as
$$
x^2 + \frac{7}{6}x - \frac{10}{6}
$$

##### If the two roots of a quadratic are $\alpha = -2$ and $\beta = 5$, how could you write the quadratic??
$$
x^2 + 3x - 10
$$

##### If $\alpha + \beta = -\frac{5}{6}$ and $\alpha\beta = \frac{1}{6}$, how could you write a quadratic with integer coefficients that has those roots??
$$
6x^2 - 5x + 1
$$

##### What is the last coefficient in a polynomial always equal to??
Plus or minus the product of the roots.

##### What is the second coefficient in a polynomial always equal to??
The negative sum of the roots.

##### What do cubics and quartics have on top of sums of roots and products of roots??
Sum of product of pairs.

##### What do quartics have on top of sums of roots, products of roots and the sum of products of pairs??
Sum of products of triples.

##### For any polynomial, the second coefficient always tells you??
The negative sum of the roots.

##### After the negative sum of the roots, how can you work out the sign for the coefficients??
It alternates, so the third coefficient will be positive and the fourth coefficient will be negative.

##### In a quadratic, what is the last term equal to??
The positive product of the roots.

##### In a cubic, what is the last term equal to??
The negative product of the roots.

##### In a quartic, what is the last term equal to??
The positive sum of the roots.

### Relation to the Quadratic Formula
##### What is the quadratic formula??
$$
\frac{-b \pm \sqrt{b^2 - 4ac}}{2a}
$$

##### If you have a quadratic $ax^2 + bx + c$ with roots $\alpha$ and $\beta$, how could you write $\alpha$ and $\beta$ in terms of $a,b,c$??
* $\alpha = \frac{-b + \sqrt{b^2 - 4ac}}{2a}$
* $\beta = \frac{-b - \sqrt{b^2 - 4ac}}{2a}$

##### What does adding the two results of the quadratic formula ($\pm$) leave??
$$
\frac{-b}{a}
$$

##### In terms of $\alpha$ and $\beta$, what is the result of adding the two results of the quadratic formula together??
$$
\alpha + \beta
$$

##### What does multiplying the two results of the quadratic formula ($\pm$) leave??
$$
\frac{c}{a}
$$

##### In terms of $\alpha$ and $\beta$, what is the result of multiplying the two results of the quadratic formula together??
$$
\alpha\beta
$$

##### Why is adding together the two results of the quadratic formula the sum of the roots??
The quadratic formula's results _are_ the roots of a quadratic.

##### Why is multiplying together the two results of the quadratic formula the product of the roots??
The quadratic formula's results _are_ the roots of a quadratic.

### Linear Transformations of Roots
This is still @?todo. The subsitution method involving $w$ still seems like magic to me.

##### If a quadratic's roots have been moved one to left (i.e. $2, -3$ becomes $1, -4$, then what has happened to the quadratic??
It has also been moved one to the left.

##### What transformation must a quadratic undergo for the roots to be double what they once were??
The quadratic has been stretched horizontally by a factor of two.

##### What are the two techniques for finding an equation with a linear transformation of roots??
* Using the relationship between roots and coefficients
* Using a subsititution

##### How can you find an equation with a linear transformation of roots using the relationship between roots and coefficients??
Calculating new combinations of roots (such as the sum of roots or product of roots) from a combination of the modified roots and seeing how they compare to the coefficients of the polynomial.

##### How could you rewrite $(\alpha + 1) + (\beta + 1)$ as a combination of useful $\alpha$ and $\beta$ expressions??
$$
(\alpha + \beta) + 2
$$

##### If you need to find a new equation with roots $(\alpha + 1)$ and $(\beta + 1)$ from $x^2 - 3x - 10 = 0$, what must the new sum of roots be??
* In original $\alpha + \beta = 3$
* In new $\alpha + \beta + 2 = 3 + 2 = 5$

##### What is the process for creating a new equation with roots $f(\alpha)$ and $f(\beta)$ given $ax^2 + bx + c = 0$??
* $w = f(x)$
* $x = f^{-1}(w)$
* Substitute the new value of $x$ into the original equation.

##### If you had an equation with roots $\alpha$ and $\beta$, what substitution could you make for $x$ in terms of $w$ for a new equation with roots $2\alpha + 1$ and $2\beta + 1$??
$$
x = \frac{w-1}{2}
$$

##### If you had an equation with roots $\alpha$ and $\beta$, what substitution could you make for $x$ in terms of $w$ for a new equation with roots $\frac{\alpha^2}{4} and $\frac{\beta^2}{4}??
$$
x = 2\sqrt{w}
$$

##### I have a substitution of $x = 2w$ and an equation of $3x^2 - 3x + 1$. What's the next step for creating an equation with new roots??
Rewriting the original equation in terms of $w$.

$$
3(2w)^2 - 3(2w) + 1 = 0
$$

##### What is the process for finding the value of $\alpha^2 + \beta^2 + \gamma^2 + \alpha\beta\gamma$ given the equation $x^3 + 4x + 3 = 0$??
* Break down into $\alpha^2 + \beta^2 + \gamma^2$ and $\alpha\beta\gamma$
* $\alpha\beta\gamma$ is $-3$ (i.e. the product of roots)
* Make substitution $w = \sqrt[\leftroot{-3}\uproot{3}4]{x}$
* New sum of roots for $w$ equation is $\alpha^4 + \beta^2 + \theta$

##### I want to find $\alpha^2 + \beta^2 + \gamma^2$ from the equation $x^3 + 4x + 3 = 0$. What substitution could I make??
$$
w = \sqrt{x}
$$

##### After I make the substitution $w = x^{\frac{1}{3}}$, I can get the equation $x^3 - 3x + 4 = 0$. If the original roots were $\alpha$, $\beta$ and $\gamma$, the new roots of this equation are??
$$
\alpha^3, \beta^3, \gamma^3
$$

##### How can you quickly work out the formula for the sum of triples??
Start with all 4 roots and then miss out one of them each time.

##### How many terms are there in the sum of the pairs in a quartic??
$$
6
$$

##### What does $\sum \alpha$ mean??
The sum of the roots.

##### What is the notation for the sum of the roots??
$$
\sum \alpha
$$

##### What does $\sum \alpha \beta$ mean??
The sum of the pairs.

##### What is the notation for the sum of the pairs??
$$
\sum \alpha\beta
$$

##### What does $\sum \alpha \beta \gamma$ mean??
The sum of the triples.

##### What is the notation for the sum of the triples??
$$
\sum \alpha\beta\gamma
$$

##### What $x$ choose $y$ expression could you use for finding the amount of terms in the sum of pairs for a quartic??
$$
4C2
$$

##### How could you rewrite $\frac{1}{\alpha} + \frac{1}{\beta} + \frac{1}{\gamma}$??
$$
\frac{\sum \alpha\beta}{\alpha\beta\gamma}
$$

##### How could you rewrite $\frac{1}{\alpha} + \frac{1}{\beta} + \frac{1}{\gamma} + \frac{1}{\delta}$??
$$
\frac{\sum \alpha\beta\gamma}{\alpha\beta\gamma\delta}
$$

##### What's the pattern behind the rules for $\frac{1}{\alpha} + \frac{1}{\beta} + ...$
$$
\frac{\text{sum of roots/pairs/triples}}{\text{product of roots}}
$$

##### How could you rewrite $\alpha^2 + \beta^2 + \gamma^2$??
$$
(\sum \alpha)^2 - 2(\sum \alpha \beta)
$$

##### How could you rewrite $\alpha^2 + \beta^2 + \gamma^2 + \delta^2$??
$$
(\sum \alpha)^2 - 2(\sum \alpha \beta)
$$

##### What's the pattern behind the rules for $\alpha^2 + \beta^2 + ...$??
$$
(\sum\alpha)^2 - 2(\sum\alpha\beta)
$$

(Apart from for $\alpha^2 + \gamma^2$, which is trivial to prove)

##### How could you rewrite $\alpha^3 + \beta^3$??
$$
(\alpha + \beta)^3 - 3\alpha\beta(\alpha+\beta)
$$

##### How could you rewrite $\alpha^3 + \beta^3 + \gamma^3$??
$$
(\sum \alpha)^3 - 3(\sum \alpha)(\sum \alpha \beta) + 3\alpha\beta\gamma
$$

##### How could you rewrite $(\alpha\beta)^2 + (\alpha\gamma)^2 + (\beta\gamma)^2$??
$$
(\sum\alpha\beta)^2 - 2\alpha\beta\gamma(\sum\alpha)
$$
