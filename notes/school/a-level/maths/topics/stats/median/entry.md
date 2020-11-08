---
title: "Stats - Median, Quartiles and Percentiles"
date: "2020-10-08 18:36"
---

##### What is the formula for the position of the median??
$$
\frac{n}{2}
$$

##### What is the formula for the position of the lower quartile??
$$
\frac{n}{4}
$$

##### What is the formula for the position of the upper quartile??
$$
\frac{3n}{4}
$$

##### What is the formula for the $p-th$ percentile??
$$
n \times \frac{p}{100} \\\\
\text{e.g.} 23 \times 0.57
$$

##### What is the notation for the upper quartile??
$$
Q_3
$$

##### What is the notation for the lower quartile??
$$
Q_1
$$

##### What is the notation for the median??
$$
Q_2
$$

##### What is the notation for the $57$-th percentile??
$$
P_{57}
$$

##### What are the rounding rules for the positions of medians, quartiles and percentiles??
* If it's a whole number, it's between the given position and the one above
* If it's a decimal, round up to the next value

##### A data set is $255$ values long, where is the median??
At position $128$.

##### A data set is $255$ values long, where is the lower quartile??
At position $64$.

##### A data set is $255$ values long, where is the upper quartile??
At position $192$.

##### A data set is $10$ values long, where is the median??
Between position $5$ and $6$.

##### What assumption are you making when you perform linear interpolation??
That the data values are evenly distributed within each class.

##### What is interpolation??
A technique for finding an estimate of quartiles or percentiles in grouped data.

##### If you have a median at culmulative frequency $26$, which lies in a group ranging from $11 \to 30$, what fraction through the class are you??
$$
\frac{26 - 11}{30 - 11}
$$

##### What is the formula for linear interpolation in stats??
$$
\text{bottom of class} + \text{class width} \times \text{fraction through class}
$$

##### Can you adjust $$10-50 \\\\ 51-100$$ so that the class boundries overlap, assuming the variable measured is $w$, weight??
$$
9.5 \leq w < 50.5 \\\\ 50.5 \leq w < 100.5
$$

##### Can you adjust $$10-50 \\\\ 51-100$$ so that the class boundries overlap, assuming the variable measured is $a$, age??
$$
10 \leq a < 51 \\\\ 51 \leq a < 101
$$

##### Why do you have to be careful adjusting class boundries for age??
Consider that somebody is still considered 20 if it's one day before their 21st birthday, it's always rounded down.

##### What common measurement do you need to be careful adjusting class boundries for??
Age.

##### What is $D_{1}$ as a percentile??
$$
P_{10}
$$

