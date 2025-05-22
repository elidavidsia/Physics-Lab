# Problem 2

## Escape Velocities and Cosmic Velocities

The study of velocities in celestial mechanics is fundamental to understanding how spacecraft can break free from a planet’s gravitational pull, enter orbit, or leave the solar system. These velocities are typically categorized as escape velocities and cosmic velocities. The escape velocity is the speed needed to break free from a planet’s gravitational field, while cosmic velocities define the different thresholds for orbital and interstellar escape.

#### Types of Cosmic Velocities

- First Cosmic Velocity (Orbital velocity)
- Second Cosmic Velocity (Escape velocity)
- Third Cosmic Velocity (Escape velocity from the Solar System)

<br>
<hr>
<br>

## 1. Definitions and Physical Meaning

### Escape Velocity

The escape velocity is the minimum speed an object needs to escape the gravitational pull of a celestial body, such as Earth, without further propulsion. This velocity depends on the mass and radius of the body from which the object is escaping. The formula for escape velocity is:

$$
v_e = \sqrt{\frac{2GM}{R}}
$$

Where:

- **G** = gravitational constant $6.67430 \times 10^{-11} \, \text{m}^3 \, \text{kg}^{-1} \, \text{s}^{-2}$
- **M** = mass of the celestial body (kg)
- **R** = radius of the celestial body (m)

### First Cosmic Velocity

The first cosmic velocity is the speed an object must have to remain in a stable circular orbit around a celestial body. This is the orbital velocity:

$$
v_1 = \sqrt{\frac{GM}{R}}
$$

### Second Cosmic Velocity

The second cosmic velocity, or escape velocity, is the speed needed to escape the gravitational pull of a celestial body entirely, without falling back to it. As mentioned above, this is given by the same formula:

$$
v_2 = \sqrt{\frac{2GM}{R}}
$$

### Third Cosmic Velocity

The third cosmic velocity is the escape velocity required to escape the Sun’s gravitational influence and leave the Solar System entirely:

$$
v_3 = \sqrt{\frac{2GM_{\text{sun}}}{R_{\text{sun}}} + \frac{2GM_{\text{planet}}}{R_{\text{planet}}}}
$$

<br>
<hr>
<br>

## 2. Mathematical Derivations

We start by considering the energy required to escape a celestial body. The total mechanical energy $E$ of an object in a gravitational field is the sum of its kinetic energy $K$ and gravitational potential energy $U$.

**Gravitational Potential Energy:**

$$
E = K + U = \frac{1}{2} mv^2 - \frac{GMm}{R}
$$

For escape, we need the total energy to be zero (the object should just reach infinity with zero speed). Therefore:

$$
\frac{1}{2} mv^2 = \frac{GMm}{R}
$$

Solving for escape velocity:

$$
v_e = \sqrt{\frac{2GM}{R}}
$$

<br>
<hr>
<br>

## 3. Analysis and Calculation

Now, let's calculate and visualize the first, second, and third cosmic velocities for Earth, Mars, and Jupiter.


### Parameters

**Earth:**  
Mass of Earth ($M_{\text{Earth}}$) = $5.972 \times 10^{24}$ kg  
Radius of Earth ($R_{\text{Earth}}$) = $6.371 \times 10^6$ m


**Mars:**  
Mass of Mars ($M_{\text{Mars}}$) = $6.417 \times 10^{23}$ kg  
Radius of Mars ($R_{\text{Mars}}$) = $3.396 \times 10^6$ m


**Jupiter:**  
Mass of Jupiter ($M_{\text{Jupiter}}$) = $1.898 \times 10^{27}$ kg  
Radius of Jupiter ($R_{\text{Jupiter}}$) = $6.991 \times 10^7$ m


**Sun:**  
Mass of Sun ($M_{\text{Sun}}$) = $1.989 \times 10^{30}$ kg


**Distance from Earth to Sun:**  
$R_{\text{Earth-Sun}}$ = $1.496 \times 10^{11}$ m

<br>

### Visualization and Calculation

Using the given parameters, we can now calculate the escape velocities, orbital velocities, and third cosmic velocities for Earth, Mars, and Jupiter. The calculations depend on the mass and radius of each celestial body, and for the third cosmic velocity, the gravitational influences of both the planet and the Sun are considered.

<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/2%20Gravity/Problem%202a.png">

<br>

<img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/refs/heads/main/docs/1%20Physics/2%20Gravity/Problem%202b.png">

<br>

By calculating these values, we can understand the differences in velocities required for escape, orbit, and interstellar travel from different celestial bodies.

<br>
<hr>
<br>

## 4. Importance In Space Exploration

Understanding these velocities is crucial for space missions:

- **Launching Satellites:** To place satellites into orbit around Earth or another body, the first cosmic velocity is used to determine the speed at which to launch.
- **Interplanetary Missions:** The second cosmic velocity is necessary for spacecraft to leave the planet’s gravity and travel to other planets, such as Mars or Jupiter.
- **Interstellar Travel:** The third cosmic velocity would be required for any spacecraft attempting to travel outside the Solar System.

<br>
<hr>
<br>

## 5. Conclusion

The study of escape and cosmic velocities provides critical insight into the dynamics of space travel and celestial mechanics. These velocities define the thresholds necessary for an object to break free from a planet’s gravitational influence, achieve stable orbits, or venture beyond the Solar System.

- **Escape velocity** is fundamental for launching spacecraft or objects into space, ensuring they overcome a planet's gravitational pull.
- **First cosmic velocity** is essential for maintaining orbits around celestial bodies, such as Earth, and is used in satellite deployment and orbital missions.
- **Second cosmic velocity** allows spacecraft to leave the gravitational pull of a planet entirely, enabling interplanetary missions like those to Mars or Jupiter.
- **Third cosmic velocity** provides the required speed for interstellar travel, which is essential for missions aiming to explore regions beyond our Solar System.

The calculations and visualizations for Earth, Mars, and Jupiter illustrate how these velocities vary with the mass and size of celestial bodies, demonstrating the challenges involved in space exploration. Understanding these velocities is crucial for both current and future space missions, as they directly impact mission design, energy requirements, and the success of interplanetary and interstellar exploration.

<br>

