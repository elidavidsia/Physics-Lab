# Problem 1

## Exploring the Central Limit Theorem through Simulations

The Central Limit Theorem (CLT) is a foundational principle in statistics that explains why the normal distribution appears so frequently in practice. It states that, given a sufficiently large sample size, the sampling distribution of the sample mean will tend to be normally distributed regardless of the shape of the population distribution. This task uses simulations to explore and visualize this phenomenon.

<br><hr><br>

## 1. Exploration of Applications

The CLT underpins many statistical procedures and real-world practices. In **survey sampling**, it allows researchers to estimate population parameters even when the population distribution is unknown. In **quality control**, it provides a basis for monitoring product consistency by assessing sample means. In **finance**, it supports modeling average returns and risk over time.

Understanding the CLT enables more accurate predictions, better experimental designs, and sound inference from sample data in both scientific research and applied settings.

<br><hr><br>

## 2. Theory and Mathematical Formulation

The Central Limit Theorem can be summarized as:

<center><strong>Central Limit Theorem:</strong></center>

$$
\bar{X}_n = \frac{1}{n} \sum_{i=1}^{n} X_i \xrightarrow{d} \mathcal{N}(\mu, \frac{\sigma^2}{n}) \text{ as } n \to \infty
$$

##### Where:

- **$\bar{X}_n$**: Sample mean  
- **$X_i$**: Independent and identically distributed random variables from any population  
- **$\mu$**: Population mean  
- **$\sigma^2$**: Population variance  
- **$n$**: Sample size  

As the sample size increases, the distribution of \$\bar{X}\_n\$ approaches a normal distribution with mean \$\mu\$ and variance \$\frac{\sigma^2}{n}\$, even if the original population is not normally distributed.

<br><hr><br>

## 3. Python Simulation

<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/6%20Statistics/Problem1a.png">
<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/6%20Statistics/Problem1b.png">
<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/6%20Statistics/Problem1c.png">

<br><hr><br>

## 4. Parameter Exploration

This simulation explores the CLT across different population distributions:

* **Uniform Distribution \[0, 10]**
* **Exponential Distribution (λ = 0.5)**
* **Binomial Distribution (n = 10, p = 0.5)**

For each population:

* Vary the **sample size**: 5, 10, 30, 50
* Observe the **sampling distribution of the mean**
* Track how quickly the distribution approaches normality

You can also investigate:

* **Skewness and kurtosis** to quantify deviation from normality
* The effect of **population variance** on the spread of sample means

<br><hr><br>

## 5. Conclusion

The Central Limit Theorem is essential in statistics because it provides a bridge between arbitrary population distributions and the normal distribution. Simulations demonstrate that, regardless of how skewed or discrete the population is, the distribution of sample means becomes increasingly normal as the sample size grows. This convergence is crucial in enabling statistical inference and justifying the use of confidence intervals and hypothesis testing in diverse real-world applications.

The insights gained from simulation deepen our understanding of this powerful theorem and reinforce its practical significance across science, industry, and data-driven decision-making.

<br>

Would you like the accompanying Python code as a standalone script or embedded in a Jupyter Notebook next?
