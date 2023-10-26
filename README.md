# ECM1416-Computational-Mathematics-Coursework

Code produced for the ECM1316 Computational Mathematics Module Coursework

# Question 1
Consider a diagram made up of four parts, where in each part we have points in $R^2,P=(x,y)$,
connected with a line in the order of the arrows, so for example
*P1 → P2 → P3*, then *P4 → P1*
means connecting *P1* to *P2* then *P2* to *P3*; and then connecting *P4* to *P1*. The coordinates of the points in each part
are given below, where $a∈R$.

- Part 1: $(a,a)→(a,−a)→(−a,−a)→(−a,a)→(a,a)$.
- Part 2: $(1−a,a−1)→(−a/4,a−1)→(−a/4,a/2)→(1−a,a/2)→(1−a,a−1)$.
- Part 3: $(a/4,a−1)→(a−1,a/2)$, then $(a−1,a−1)→(a/4,a/2)$.
- Part 4: $(a−1,−a/4)→(a−1,−a/2)→(1−a,−a/2)→(1−a,−a/4)$.

Let A be a matrix defined by

$$A = \frac{1}{b} \begin{bmatrix}b & 1\\
-1 & b \end{bmatrix}$$

Tasks:

1. Write a program that performs the transformation of points in Parts 1-4 induced by matrix A.
2. Let a = 4 and b = 3, run your program and output two figures, a figure showing the diagram produced before
the transformation, and a figure showing the diagram after the transformation.

# Question 2
Consider the following initial value problem,

$$\frac{dy}{dx} = x + \frac{y}{5}$$
$$y(0) = -3$$

Tasks:

1. Write a program to apply the Euler’s method to obtain the numerical (approximated) solution, with step sizes
of 1, 0.2, and 0.05 on the interval [0, 5], respectively.
2. Work out the analytical (exact) results. Plot figures to compare the numerical results to the analytical results
on the interval [0, 5]. Discuss the comparison results.
