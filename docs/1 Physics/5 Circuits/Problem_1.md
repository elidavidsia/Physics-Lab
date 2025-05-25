# Problem 1

## Equivalent Resistance Using Graph Theory

Calculating equivalent resistance is a fundamental problem in electrical circuits, essential for understanding and designing efficient systems. While traditional methods involve iteratively applying series and parallel resistor rules, these approaches can become cumbersome for complex circuits with many components. Graph theory offers a powerful alternative, providing a structured and algorithmic way to analyze circuits.

By representing a circuit as a graph—where nodes correspond to junctions and edges represent resistors with weights equal to their resistance values—we can systematically simplify even the most intricate networks. This method not only streamlines calculations but also opens the door to automated analysis, making it particularly useful in modern applications like circuit simulation software, optimization problems, and network design.

Studying equivalent resistance through graph theory is valuable not only for its practical applications but also for the deeper insights it provides into the interplay between electrical and mathematical concepts. This approach highlights the versatility of graph theory, demonstrating its relevance across physics, engineering, and computer science.

<br><hr><br>

## 1. Motivation and Applications

Traditional techniques of circuit simplification become inefficient as circuit complexity increases. Graph theory allows us to represent circuits as mathematical graphs, where junctions are nodes and resistors are edges with weights representing resistance. This method enables automated simplification and analysis, making it ideal for use in circuit design tools, optimization systems, and educational software.

Beyond automation, this approach also bridges electrical engineering and discrete mathematics, deepening our understanding of how graph structures relate to physical systems.

<br><hr><br>

## 2. Theory and Mathematical Formulation

**Series Combination:**

$$
R_{\text{eq}} = R_1 + R_2
$$

**Parallel Combination:**

$$
\frac{1}{R_{\text{eq}}} = \sum_{i=1}^{n} \frac{1}{R_i}
$$

Using these rules, we can iteratively reduce the graph by:

- Identifying nodes with exactly two connections (series)
- Collapsing multiple edges between the same nodes (parallel)

This continues until the circuit is reduced to a single equivalent resistance between the source and target nodes.

<br><hr><br>

## 3. Python Simulation

Test: Series: 2Ω + 3Ω

<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/5%20Circuits/Circuit1.png">

Equivalent resistance between 1 and 3: 5.00 Ω

<br>

Test: Parallel: 2Ω || 3Ω

<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/5%20Circuits/Circuit2.png">

Equivalent resistance between 1 and 2: 3.00 Ω

<br>

Test: Nested Triangle: 1-2-3 with 2Ω, 4Ω, and 6Ω

<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/5%20Circuits/Circuit3.png">

<br><hr><br>

## 4. Conclusion</h3>
Graph-based methods for computing equivalent resistance provide a structured, scalable, and automatable solution for analyzing circuits. They work beyond simple rules and can handle complex configurations through consistent graph reduction. The approach not only streamlines engineering workflows but also illustrates the power of graph theory in solving real-world problems.

This method lays a strong foundation for more advanced applications, such as symbolic circuit analysis, automated verification, and electrical network optimization.

<br>



