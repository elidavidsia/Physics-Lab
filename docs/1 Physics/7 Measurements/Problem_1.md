# Problem 1

## Measuring Earth's Gravitational Acceleration with a Pendulum

The acceleration due to gravity is a fundamental constant that influences a wide range of physical phenomena. Measuring \$g\$ accurately is crucial for understanding gravitational interactions, designing structures, and conducting experiments in various fields. One classic method for determining \$g\$ is through the oscillations of a simple pendulum, where the period of oscillation depends on the local gravitational field.

This task explores how to measure \$g\$ using a simple pendulum, along with detailed uncertainty analysis.

<br>
<hr>
<br>

## 1. Setup and Materials

#### 1.1 Materials

* String (1 or 1.5 meters long)
* Small weight (e.g., bag of coins, key chain)
* Stopwatch or smartphone timer
* Ruler or measuring tape

<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/7%20Measurements/Materials.jpg">

<br>

#### 1.2 Setup

1. Attach the weight to the string and fix the other end to a sturdy support.
2. Measure the length \$L\$ of the pendulum from the suspension point to the center of the mass using a ruler or measuring tape. Record the uncertainty in the measurement. This uncertainty is typically half the resolution of the measuring tool used.
3. Displace the pendulum slightly (less than 15°) and release it to start oscillating.
4. Measure the time for 10 full oscillations using the stopwatch. Repeat this measurement 10 times to minimize random error.

<br>
<hr>
<br>

## 2. Data Collection and Calculations

<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/7%20Measurements/Data.jpg">

#### 2.1 Period Calculation

The period \$T\$ for one full oscillation is the time for 10 oscillations divided by 10:

$T = \frac{t_{\text{total}}}{10}$

<br>

#### 2.2 Acceleration Due to Gravity Calculation

Using the formula for the period of a simple pendulum, the acceleration due to gravity \$g\$ can be determined as:

$g = \frac{4\pi^2 L}{T^2}$

<br>

#### 2.3 Uncertainty Propagation

Uncertainty in the length \$L\$ and the period \$T\$ propagate into the uncertainty in \$g\$. Using error propagation formulas:

$\left(\frac{\Delta g}{g}\right)^2 = \left(\frac{\Delta L}{L}\right)^2 + \left(2 \frac{\Delta T}{T}\right)^2$

Thus, the uncertainty in \$g\$ is:

$\Delta g = g \sqrt{\left(\frac{\Delta L}{L}\right)^2 + \left(2 \frac{\Delta T}{T}\right)^2}$

<br>
<hr>
<br>

## 3. Uncertainty Analysis

#### 3.1 Measurement Resolution

The uncertainty in the length \$L\$ is typically small but significant, especially if the length is measured inaccurately. A 1% error in measuring \$L\$ leads to a roughly 2% error in \$g\$.

<br>

#### 3.2 Variability in Timing

Timing errors can accumulate, especially for small periods or long measurement times. Using a precise timing device (like a smartphone timer with high resolution) and ensuring consistent oscillations can reduce these errors.

<br>

#### 3.3 Assumptions

The experiment assumes:

* The pendulum swings with small amplitude (less than 15°).
* The string is massless and does not stretch.
* Air resistance is negligible.
* The motion is simple harmonic (valid for small angles).

<br>
<hr>
<br>

## 4. Python Simulation

<div style="text-align: center;">
  <a href="https://pythonsimulation-dkmyzmcmwhdipw7tgdpzuq.streamlit.app/" target="_blank">
    <button style="
      background-color: #007bff; 
      color: white; 
      padding: 12px 28px; 
      font-size: 16px; 
      border: none; 
      border-radius: 6px; 
      cursor: pointer;
      text-decoration: none;
    ">
      🚀 Launch Simulation
    </button>
  </a>
</div>

<br>
<hr>
<br>

## 5. Conclusion

In this experiment, we used the oscillations of a simple pendulum to measure the acceleration due to gravity, \$g\$. The uncertainties in the length measurement and timing were carefully considered, and their effects on the final result were propagated using error analysis techniques. The resulting value for \$g\$ was compared with the known standard value of 9.81 m/s². This experiment highlights the importance of precise measurements and careful uncertainty analysis in experimental physics.

<br>
