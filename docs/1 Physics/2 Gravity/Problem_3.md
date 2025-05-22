# Problem 3

## Trajectories of a Freely Released Payload Near Earth

When an object is released from a moving rocket near Earth, the trajectory it follows is strongly influenced by its initial conditions (position, velocity, and altitude) and gravitational forces. This problem intersects orbital mechanics, gravitational physics, and numerical simulation techniques. By understanding the possible trajectories (such as parabolic, hyperbolic, and elliptical), we can model and predict the behavior of payloads in space. This knowledge is particularly important in missions involving satellite deployment, reentry, and escape trajectories.

<br>
<hr>
<br>

## 1. Theoretical Background

### Gravitational Force

Newton's law of universal gravitation states that any two masses attract each other with a force that is proportional to the product of their masses and inversely proportional to the square of the distance between their centers of mass:

$$
F = G \frac{m_1 m_2}{r^2}
$$

Where:

- **F** = gravitational force  
- **G** = $6.67430 \times 10^{-11} \, \text{m}^3 \, \text{kg}^{-1} \, \text{s}^{-2}$  
- **$m_1$, $m_2$** = masses of two objects  
- **r** = distance between their centers  

### Kepler’s Laws

- **First Law:** The orbit of a planet (or object) around the Sun (or Earth) is an ellipse with the Sun (or Earth) at one of the foci.
- **Second Law:** A line connecting a planet to the Sun sweeps out equal areas in equal times, meaning that the object moves faster when closer to the central body.
- **Third Law:** $T^2 \propto a^3$, where $T$ is period, $a$ is semi-major axis.

### Types of Orbits

- **Elliptical Orbit:** This occurs when the object’s velocity is such that the gravitational pull of Earth results in the object moving in an elliptical path around Earth.
- **Parabolic Trajectory:** This is a special case of elliptical orbits where the eccentricity of the orbit is exactly 1. This type of trajectory occurs when an object has just enough energy to escape Earth's gravitational pull.
- **Hyperbolic Trajectory:** This occurs when the object’s velocity is higher than the escape velocity, meaning it will escape Earth’s gravitational influence entirely.

<br>
<hr>
<br>

## 2. Task Breakdown

#### Initial Conditions

Specify position and velocity vector of the payload at release.

#### Computational Modeling

Use Newton's laws and numerical methods like Runge-Kutta or Euler’s method to simulate the motion.

#### Simulating the Trajectory

- Gravitational acceleration at every point in the trajectory  
- Initial release velocity affects path type  
- Varying distance from Earth affects gravitational force  

#### Plotting the Trajectories

- Altitude vs. Time  
- Velocity vs. Time  
- Cartesian Trajectory (x vs. y)  

#### Escape Velocity

The escape velocity at a distance $r$ from Earth's center is:

$$
v_{\text{escape}} = \sqrt{\frac{2GM}{r}}
$$

Where:

- **G** = gravitational constant  
- **M** = mass of Earth ($5.972 \times 10^{24}$ kg)  
- **r** = distance from Earth’s center  

<br>
<hr>
<br>

## 3. Python Simulation

<div style="text-align: center;">
  <a href="https://pythonsimulation-5u2hdv5p42ucx3wp2sbzua.streamlit.app/" target="_blank">
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
<br>
<hr>
<br>

## 4. Conclusion and Applications

- **Orbital Insertion:** Proper velocity enables stable orbit.
- **Escape Trajectory:** High enough velocity leads to escape.
- **Reentry:** Insufficient speed results in falling back to Earth.

Understanding these scenarios allows mission planners to safely and accurately deliver payloads into space, return them, or launch them on interplanetary or interstellar journeys.

<br>
