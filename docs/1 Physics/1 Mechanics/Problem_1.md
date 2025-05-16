# Problem 1

## Investigating the Range as a Function of the Angle of Projection

Projectile motion is a key concept in physics, offering valuable insights into the fundamental laws of motion. By investigating how the range of a projectile changes with its angle of projection, we delve into both simple and complex relationships, characterized by linear and quadratic equations. These equations allow us to explore the influence of variables such as initial velocity, gravitational acceleration, and launch height. Understanding the dynamics of projectile motion opens up numerous real-world applications, from the arc of a soccer ball to the trajectory of a rocket.

This investigation not only provides a theoretical foundation but also extends to practical applications. By simulating projectile motion under various initial conditions, we can visualize the relationship between the angle of projection and the range. The task encourages a deeper understanding of how different parameters—such as velocity and gravity—affect motion, while also highlighting the limitations of idealized models. Incorporating more realistic factors, like air resistance, offers opportunities for further exploration in fields ranging from engineering to astrophysics.

<br>
<hr>
<br>

### 1. Theoretical Foundation
Projectile motion is governed by the following key equations, assuming no air resistance and that the only force acting on the projectile is gravity:
  
  
### Equations of Motion:

#### <center>In the horizontal direction:</center>
$$ x(t) = v_0 \cdot \cos(\theta) \cdot t $$

#### <center>In the vertical direction:</center>
$$ y(t) = v_0 \cdot \sin(\theta) \cdot t - \frac{1}{2} g t^2 $$
  
##### Where:
$x(t)$ and $y(t)$ are the horizontal and vertical positions of the projectile at time $t$.
<br>
$v_0$ is the initial velocity.
<br>
$θ$ is the angle of projection.
<br>
$g$ is the gravitational acceleration.
  
The range $R$ is the horizontal distance traveled by the projectile when it returns to the ground (i.e., when $y(t) = 0$
  
<center>To find the time $T$ when the projectile hits the ground, set $y(T)=0$:</center>
  
$$ 0 = v \cdot \sin(\theta) \cdot T - \frac{1}{2} g T^2 $$  

<center>Solving for $T$:  </center>
  
$$ T = \frac{g}{2v \sin(\theta)} $$  
  
<center>Substitute this time into the horizontal motion equation to find the range:</center>

$$ R = v \cdot \cos(\theta) \cdot T $$  

$$ R = \frac{g}{v_0^2} \cdot \sin(2\theta) $$

<br>
<hr>
<br>

## 2. Analysis of the Range

The range $R$ depends on several factors:

- **Angle of projection \( \theta \)**: The range is maximized when \( \sin(2\theta) = 1 \), which occurs at \( \theta = 45^\circ \). The range decreases as the angle of projection moves away from \( 45^\circ \), either increasing or decreasing.

- **Initial velocity \( v_0 \)**: As the initial velocity increases, the range increases quadratically. This is reflected in the \( v_0^2 \) term in the range formula.

- **Gravitational acceleration \( g \)**: The range is inversely proportional to \( g \), meaning that the higher the gravitational acceleration, the shorter the range. On Earth, \( g \approx 9.8 \, \text{m/s}^2 \).

<br>
<hr>
<br>

## 3. Practical Applications
This idealized model can be adapted to more complex situations such as:

- **Uneven Terrain**  
  If the projectile lands at a height different from its launch height, we would need to modify the equations to account for the initial and final vertical positions.

- **Air Resistance**  
  Air resistance causes the projectile to decelerate in both horizontal and vertical directions. This requires solving a set of differential equations considering drag force.

- **Sports**  
  Understanding the trajectory of a soccer ball, basketball, or baseball allows athletes to optimize their throws or kicks.
  
- **Astrophysics**  
  The range equation can be adapted for space exploration to model the trajectory of spacecraft under gravitational forces.

<br>
<hr>
<br>

## 4. Implementation
### <center>Python Simulation</center>
<p align="center">
  <img src="https://raw.githubusercontent.com/elidavidsia/Physics-Lab/main/docs/1%20Physics/1%20Mechanics/Problem1.jpg">
</p>

<br>
<hr>
<br>

## 5. Conclusion
In conclusion, the investigation of projectile motion as a function of the angle of projection provides valuable insights into the interplay of physical variables such as initial velocity, gravitational acceleration, and launch height. By deriving and analyzing the governing equations, we understand how the angle of projection significantly influences the range, with a 45° angle typically maximizing the distance traveled by the projectile. 

The practical applications of this model extend beyond theoretical physics into real-world scenarios like sports, engineering, and even space exploration, where understanding projectile trajectories is crucial. While the idealized model serves as a strong foundation, it is important to acknowledge its limitations, particularly in the presence of air resistance or varying terrain. By incorporating numerical simulations and exploring more complex models, we can better account for these factors, providing a more accurate representation of real-world projectile motion. Ultimately, this task deepens our understanding of projectile motion and showcases its broad applicability across various fields.

<br>
