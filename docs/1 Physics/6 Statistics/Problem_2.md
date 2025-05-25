# Problem 2

## Estimating Pi Using Monte Carlo Methods

Monte Carlo simulations are a powerful class of computational techniques that use randomness to solve problems or estimate values. One of the most elegant applications of Monte Carlo methods is estimating the value of $\pi$ through geometric probability. By generating random points and analyzing their positions relative to a geometric shape, we can approximate $\pi$ in an intuitive and visually engaging way.

This task explores two Monte Carlo approaches for estimating $\pi$:

- **Using a Circle and a Square**: Estimating $\pi$ based on the ratio of points inside a circle to the total number of points in a square.
- **Buffon’s Needle**: Estimating $\pi$ based on the probability of a needle crossing parallel lines on a plane.

We will explore the theoretical foundations of these methods, simulate them using Python, visualize the results, and analyze the convergence rates and computational considerations.

<br>
<hr>
<br>

## 1. Estimating $\pi$ Using a Circle

### 1.1 Theoretical Foundation

Consider a unit circle inscribed within a square. The area of the circle is

$$
A_{\text{circle}} = \pi r^2 = \pi
$$  

(since $r = 1$ for the unit circle), and the area of the square is  

$$
A_{\text{square}} = 4
$$  

(since the side length of the square is 2).

Now, if we randomly generate points in the square and count how many fall inside the circle, the ratio of points inside the circle to the total points should be proportional to the ratio of the areas:

$$
\frac{\text{Points inside the circle}}{\text{Total points}} \approx \frac{A_{\text{circle}}}{A_{\text{square}}} = \frac{\pi}{4}
$$

Thus, we can estimate $\pi$ using the following formula:

$$
\pi \approx 4 \times \frac{\text{Points inside the circle}}{\text{Total points}}
$$

### 1.2 Simulation

To estimate $\pi$, we generate random points within a square of side length 2, centered at the origin. We check if each point lies inside the unit circle using the condition $x^2 + y^2 \leq 1$, and then estimate $\pi$ by multiplying the ratio of points inside the circle by 4.

### 1.3 Visualization

Below is a visualization of the Monte Carlo simulation for estimating $\pi$ using a circle-based method, where points inside the circle are shown in blue and those outside are shown in red.

<center>
<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/6%20Statistics/Problem2a.png">
</center>

<br>
<hr>
<br>

## 2. Estimating $\pi$ Using Buffon’s Needle

### 2.1 Theoretical Foundation

Buffon's Needle is a probability problem that involves a needle of length $L$ dropped on a floor with parallel lines spaced $D$ units apart. The probability $P$ that the needle will cross a line is given by:

$$
P = \frac{2L}{\pi D}
$$

Rearranging this formula to estimate $\pi$, we get:

$$
\pi = \frac{2L}{P D}
$$

For simplicity, we'll assume $L = D$, so the formula simplifies to:

$$
\pi = \frac{2N}{k}
$$

##### Where:

- **$N$**: Total number of needle drops.
- **$k$**: Number of times the needle crosses a line.

### 2.2 Simulation

To estimate $\pi$ using Buffon’s Needle, we randomly simulate the drop of a needle on the plane with parallel lines. We count the number of times the needle crosses a line and estimate $\pi$ based on the formula.

### 2.3 Visualization

Below is a graphical representation of the simulation, showing the needle positions relative to the lines.

<center>
<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/6%20Statistics/Problem2b.png">
</center>

<br>
<hr>
<br>

## 3. Conclusion

Both Monte Carlo methods—estimating $\pi$ using a circle and a square, and Buffon’s Needle—provide insightful and computationally efficient ways to estimate $\pi$. The circle-based method is based on geometric probability and visually intuitive, while Buffon’s Needle is a fascinating example of how randomness in geometric settings can yield surprising results.

In both cases, the accuracy of the estimates improves as the number of iterations increases. The convergence rate of each method can be compared, and insights into their computational efficiency can be drawn. Further analysis can reveal how the methods behave with different sample sizes and the time taken for convergence.

<br>
