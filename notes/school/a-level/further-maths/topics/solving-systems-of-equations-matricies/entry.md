---
title: "Further Maths - Solving Systems of Equations Using Matricies"
date: "2020-09-25 18:40"

tags: ["@?further-maths", "@?latex-block-alt"]
---

##### What is the crucial idea that allows you to solve systems of equations using matricies??
If

$$
A\left( \begin{matrix} x \\\\ y \\ z\end{matrix} \right) = v
$$

then

$$
\left( \begin{matrix} x \\\\ y \\ z\end{matrix} \right) = A^{-1}v
$$

##### How could you rewrite \[2x+3y = 4 \\\\ 4x-y = 7\] as the product of two matricies??
$$
\left(\begin{matrix}2 & 3 \\\\ 4 & -1\end{matrix}\right)\left(\begin{matrix}x \\ y\end{matrix}\right) = \left(\begin{matrix}4 \\ 7\end{matrix}\right)
$$

##### How could you solve this $$\left(\begin{matrix}2 & 3 \\\\ 4 & -1\end{matrix}\right)\left(\begin{matrix}x \\ y\end{matrix}\right) = \left(\begin{matrix}4 \\ 7\end{matrix}\right)$$??
Multiply both left-hand sides of the equation by the inverse of the matrix.

##### How could you rewrite $$2x-6y+4z = 32 \\\\ 3x + 2y -9z = -49 \\ -2x + 4y + z = -3$$ (the jist is fine, not exact)??
$$
\left( \begin{matrix} 2 & -6 & 4 \\\\ 3 & 2 & -9 \\ -2 & 4 & 1\end{matrix} \right) = \left( \begin{matrix} 32 \\ -49 \\ -3\end{matrix} \right)
$$

##### What does it mean for a system of equations to be consistent??
There is at least one set of values that satisfies all three equations simulataneously.

##### What does it mean for a system of equations to be inconsistent??
There are no sets of values that satisfy all three equations simulatanaeously.

##### What is the geometric visualisation of three planes meeting at a point??
PHOTO

##### What does it mean in terms of the number of solutions for three planes meeting at a point??
The system of equations is consistent and has only one solution.

##### If a system of equations is consistent and only has one solution, then the planes form??
A point.

PHOTO

##### What is the geometric visualisation of three planes forming a sheaf??
PHOTO

##### What does it mean in terms of the number of solutions and consistency for three planes forming a sheaf??
The system of equations is consistent and has infintely many solutions along a line.

##### If a system of equations is consistent and has infinitely many solutions along a line, then the planes form??
A sheaf.

PHOTO

##### What does it mean in terms of the number of solutions and consistency for three planes being parallel and non-identical??
The system of equations is inconsistent and has no solutions.

##### What is the geometric visualisation of two or more planes being parallel and non-identical??
PHOTO

##### If a system of equations is inconsistent and has no solutions, then the planes can form what two scenarios??
* A prism
* Two or more parallel, non-identical planes

##### What does it mean in terms of the number of solutions and consistency for three planes forming a prism??
The system of equations is inconsistent and has no solutions.

##### What is the geometric visualisation of two or more planes forming a prism??
PHOTO

##### What does it mean in terms of the number and solutions and consistency for three identical planes??
The system of equations is consistent and has infinitely many solutions along plane.

##### What is the geometric visualisation of three planes being the same??
PHOTO

##### If a system of equations is consistent and has infinitely many solutions along a plane, then the planes form??
A plane. They're all the same.

PHOTO

##### If a system of equations is consistent but has a zero determinant, what are the two possible plane configurations??
* A sheaf
* A plane

##### Hi! I'm a system of equations. My determinant is zero, and when you try and solve me manually you get GARBAGE. What's my consistency and plane configurations??
* Inconsistent
* A triangular prism OR Parralel planes

##### Hi! I'm a system of equations. My determinant is non-zero. What's my consistency and plane configuration??
* Consistent
* Planes meet at a point

##### Hi! I'm a system of equations. My determinant is zero and when you try and solve me manually you get $0 = 0$. What's my consistency and plane configurations??
* Consistent
* A sheaf OR A it's the same plane
