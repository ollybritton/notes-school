---
title: "Further Maths - Inverting Matricies"
date: "2020-09-25 18:30"

tags: ["@?further-maths", "@?latex-block-alt"]
---

##### What is the math definition of the inverse matrix of $M$??
The inverse matrix of $M$ is the matrix $M^{-1}$ such that $MM^{-1} = M^{-1}M = I$.

##### What's the wordy definition for an inverse matrix of $M$??
The matrix that when multiplied by the original matrix yields the identity matrix.

##### What's the formula for the inverse of matrix $$M = \left( \begin{matrix}a & b \\\\ c & d\end{matrix} \right)$$??
$$
\frac{1}{\text{ad - bc} M} \left( \begin{matrix}d & -b \\\\ -c & a\end{matrix} \right)
$$

##### What's the formula for the inverse of a two by two matrix??
$$
\frac{1}{\text{ad - bc} M} \left( \begin{matrix}d & -b \\\\ -c & a\end{matrix} \right)
$$

##### How many steps are there for finding the inverse of a $3 \times 3$ matrix??
5.

##### What is step 1 for finding the inverse of a $3 \times 3$ matix??
Finding the determinant.

##### What is step 2 for finding the inverse of a $3 \times 3$ matrix??
Writing the matrix of minors.

##### What is step 3 for finding the inverse of a $3 \times 3$ matrix??
Finding the matrix of cofactors.

##### What is step 4 for finding the inverse of a $3 \times 3$ matrix??
Finding the transpose of the matrix of cofactors.

##### What is step 5 for finding the inverse of a $3 \times 3$ matrix??
Multiplying the matrix of cofactors by $\frac{1}{\text{det}(M)}$

##### What is the matrix of minors of $A$??
The matrix where each element in $A$ is replaced by its minor.

##### What's the name for a matrix that looks like this??
PHOTO

##### What does $M$ mean when finding the inverse of a $3 \times 3$ matrix??
The matrix of minors.

##### What does $C$ mean when finding the inverse of a $3 \times 3$ matrix??
The matrix of cofactors.

##### What does $C^{T}$ mean when finding the inverse of a $3 \times 3$ matrix??
The transposed matrix of cofactors.

##### What's a flowchart explanation for finding the inverse of a $3 \times 3$ matrix $A$??
$A \to M \to C \to C^T \to \frac{1}{\text{det}(A)} C^T$

##### If PHOTO is the matrix of minors, what is the matrix of cofactors??
PHOTO

##### What is the transpose of a matrix??
Where you "reflect" the matrix across the diagonal.

##### If the reflection line when finding the transpose of a matrix was a $y=mx$ equation, what would it be??
$y = -x$

##### If PHOTO is the matrix of cofactors, what is the transposed matrix of cofactors??
PHOTO

##### What is $AA^{-1}$??
$I$.

##### If $A^2 = I$, what does that tell you about $A$??
$$
A = A^{-1}
$$

##### If $A^3 = I$, what does that tell you about $A$?
$$
A^2 = A^{-1}
$$

##### What's another way of writing $(AB)^{-1}$??
$$
B^{-1}A^{-1}
$$

##### What's another way of writing $B^{-1}A^{-1}$??
$$
(AB)^{-1}
$$

##### The result that $(AB)^{-1} = B^{-1}A^{-1}$ is similar to what result in vectors??
$$
\vec{AB} = b - a
$$
