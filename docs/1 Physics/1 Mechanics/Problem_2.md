# Problem 2

## Investigating the Dynamics of a Forced Damped Pendulum

The forced damped pendulum is a fascinating example of a physical system where damping, restoring forces, and external periodic driving forces interact to produce a wide range of dynamic behaviors. From simple harmonic motion to complex phenomena like resonance, chaos, and quasiperiodic motion, this system provides a valuable framework for studying oscillatory dynamics. By exploring how factors like damping, driving amplitude, and frequency affect the pendulum's motion, we can better understand the transition between regular and chaotic behaviors, offering insights into real-world applications such as energy harvesting, vibration isolation, and mechanical resonance. <br>

This investigation delves into both the theoretical and computational aspects of the forced damped pendulum, with a focus on deriving solutions for small-angle oscillations, analyzing resonance conditions, and exploring the influence of various system parameters. By simulating and visualizing the system's behavior, we will explore the rich dynamics that emerge under different conditions, providing a deeper understanding of complex oscillatory phenomena relevant to fields ranging from engineering to physics. 

<br>
<hr>  
<br>  

## 1. Theoretical Foundation

<br>  

The dynamics of a forced damped pendulum are governed by a second-order differential equation that accounts for the restoring force due to gravity, the damping force due to friction, and the external driving force. The general equation of motion for a forced damped pendulum is:

$$\theta''(t) + \gamma \theta'(t) + \omega_0^2 \sin(\theta(t)) = F_0 \cos(\omega t)$$

<br>

##### Where:

- **$\theta(t)$**: Angular displacement as a function of time  
- **$\gamma$**: Damping coefficient  
- **$\omega_0$**: Natural frequency of the pendulum (in radians per second)  
- **$F_0$**: Amplitude of the external driving force  
- **$\omega$**: Driving frequency  
- **$t$**: Time  

<br> 

#### 1.1 Small-Angle Approximation

For small angles, we can approximate \$\sin(\theta) \approx \theta\$ (in radians), which simplifies the equation to: <br>

$\theta''(t) + \gamma \theta'(t) + \omega_0^2 \theta(t) = F_0 \cos(\omega t)$ <br>

This equation is a second-order linear differential equation with a periodic forcing term. The solutions to this equation are more straightforward to analyze and can be expressed in terms of the system's natural frequency and damping conditions. <br>

<br>  

#### 1.2 Resonance Conditions

Resonance occurs when the driving frequency \$\omega\$ is close to the natural frequency \$\omega\_0\$ of the pendulum. In this case, the amplitude of oscillations can grow significantly, leading to large displacements of the pendulum. The resonance condition is typically when: <br>

$\omega \approx \omega_0$ <br>

For damping systems, resonance is not idealized as in the undamped case but instead leads to a maximum amplitude at a certain driving frequency. The resonance behavior can be understood by examining the system's response function, which for a damped system is: <br>

$A(\omega) = \sqrt{(\omega_0^2 - \omega^2)^2 + (\gamma \omega)^2} \cdot F_0$ <br>

At resonance \$\omega = \omega\_0\$, the amplitude is maximized, and the system absorbs the maximum energy from the driving force. 

<br>
<hr>  
<br>  

## 2. Analysis of Dynamics 

#### 2.1 Influence of Damping Coefficient

The damping coefficient \$\gamma\$ affects the amplitude and the behavior of the oscillations. If \$\gamma\$ is small, the pendulum undergoes oscillations for a long time (underdamped behavior). If \$\gamma\$ is large, the pendulum will quickly settle to rest (overdamped behavior). The critical damping condition occurs when: <br>

$\gamma_{\text{crit}} = 2m\omega_0$

For overdamping \$\gamma > \gamma\_{\text{crit}}\$, the system does not oscillate but slowly returns to equilibrium. <br>

<br>  

#### 2.2 Influence of Driving Amplitude and Frequency

The amplitude \$F\_0\$ of the driving force directly affects the energy input into the system. As the amplitude increases, the oscillations grow larger, particularly near resonance. The driving frequency \$\omega\$ influences the frequency of oscillations and can result in various behaviors, including locked-in oscillations at a frequency that is a harmonic of the driving force, or chaotic motion. <br>

<br>  

#### 2.3 Transition to Chaotic Motion

For certain values of \$F\_0\$ and \$\omega\$, the system can transition from regular oscillations to chaotic motion. This occurs when the driving force interacts in a complex way with the natural frequency and damping of the system, leading to irregular, unpredictable behavior. Bifurcation diagrams, phase portraits, and Poincaré sections can help analyze these transitions. 

<br>
<hr>  
<br>  

## 3. Practical Applications

The forced damped pendulum model can be applied to a variety of real-world systems, including: <br>

<ul>  
<li><strong>Energy Harvesting:</strong> In devices that capture energy from oscillations, such as vibration-based energy harvesters, the pendulum's behavior near resonance is crucial for maximizing energy capture.</li>  
<li><strong>Suspension Bridges:</strong> These structures can experience periodic forces (e.g., from wind or traffic), and understanding resonance and damping is essential for ensuring the bridge’s stability and avoiding catastrophic failure.</li>  
<li><strong>Oscillating Circuits:</strong> In electrical systems, driven RLC circuits exhibit similar dynamics to a forced damped pendulum, where resonance and damping play crucial roles in determining the system’s behavior.</li>  
</ul>  

<br>  
<hr>  
<br>  

## 4. Implementation

In this section, we simulate the dynamics of the forced damped pendulum using numerical methods. Specifically, the Runge-Kutta method is employed to solve the differential equation governing the system's motion. The Python implementation calculates the angular displacement over time, allowing for the visualization of both the time evolution of the angle \$\theta(t)\$ and the phase portrait of the system. <br>

By solving this equation for various parameters, we gain insights into the pendulum's behavior under different damping and driving conditions. The code is designed to simulate the motion accurately and generate graphical outputs for further analysis. 

<p align="center">
  <img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/1%20Mechanics/Problem%202a.png">
</p>

<p align="center">
  <img src="https://github.com/elidavidsia/Physics-Lab/blob/main/docs/1%20Physics/1%20Mechanics/Problem%202b.png?raw=true">
</p>

<br>
<hr>
<br>

## 5. Conclusion

The forced damped pendulum is a rich and complex system that illustrates the dynamics of oscillatory motion influenced by damping and external periodic forces. By deriving the theoretical equations of motion and exploring resonance conditions, we can gain valuable insights into the system's behavior under various conditions. The transition between regular oscillations and chaotic motion highlights the intricate interplay between damping, driving amplitude, and frequency, providing a fascinating lens through which to understand complex dynamic systems. 

Through the computational simulations and analysis, we can visualize the pendulum's motion and explore its response to different driving forces. The practical applications of this model, ranging from energy harvesting to the stability of suspension bridges, underscore the relevance of understanding forced damped oscillations in real-world systems. While the model has certain limitations, such as the small-angle approximation and the assumptions of linear damping, it serves as a powerful tool for studying oscillatory behavior and can be extended to more complex scenarios.

<br>
