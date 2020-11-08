---
title: "Further Maths - Determinants"
date: "2020-09-25 17:45"

tags: ["@?further-maths", "@?latex-block-alt"]
---

##### What is the determinant of a matrix??
A special value associated with a matrix.

##### What does $|M|$ mean in the context of matricies??
The determinant of the matrix $M$.

##### What does $\text{det} M$ mean??
The determinant of matrix $M$.

##### What's the formula for the determinant of a $2x2$ matrix??
$$
ad - bc
$$

##### What is $M$ if $\text{det} M$ is $0$??
$M$ is a singular matrix.

##### What is $M$ if $\text{det} M$ is __not__ $0$??
$M$ is a non-singular matrix.

##### The determinant of a singular matrix is??
$0$.

##### What is special about singular matricies??
They do not have an inverse.

##### What is the determinant for $$\left( \begin{matrix}a & b \\ c & d\end{matrix} \right)$$??
$ad-bc$

##### What is the determinant for $$\left( \begin{matrix}6 & 5 \\ 1 & 2\end{matrix} \right)$$??
$7$.

##### What is the minor of an element in a matrix??
The determinant of the matrix that remains after the row and column containing that elemnt have been crossed out.

##### What is the process, but not the formula, for finding the determinant of a $3 \times 3$ matrix??
Reduce the $3 \times 3$ matrix to the combined determinants of $3$ $2\times2$ matricies.

##### What is the minor of 5 in the matrix $$\left( \begin{matrix} 1 & 5 & 1 \\ 2 & 0 & 3 \\ 6 & 5 & 4 \end{matrix} \right)$$??
* $2 \times 4 - 3 \times 6$
* $-10$

##### What is the minor of 7 in the matrix $$\left( \begin{matrix} 5 & 0 & 2 \\ -1 & 8 & 1 \\ 6 & 7 & 3 \end{matrix} \right)$$??
$7$.

##### What is the order of pluses and minuses in a matrix when finding the determinant??
$$
\left( \begin{matrix} + & - & + \\ - & + & - \\ + & - & + \end{matrix} \right)
$$

##### What is the formula for the determinant of $$\left( \begin{matrix} a & b & c \\ d & e & f \\ g & h & i  \end{matrix} \right)$$??
$$
a \times \text{det}\left( \begin{matrix} e & f \\ h & i  \end{matrix} \right) - b \times \text{det}\left( \begin{matrix} d & f \\ g & i  \end{matrix} \right) + c \times \text{det}\left( \begin{matrix} d & e \\ g & h  \end{matrix} \right)
$$

##### In one sentence, describe how you find the determinant of a $3 \times 3$ matrix??
Find the determinant of the minor of each item in one row or column and add or subtract them according to the rule of alternating signs.
