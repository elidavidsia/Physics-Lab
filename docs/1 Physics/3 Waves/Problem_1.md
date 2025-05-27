# Problem 1


## Interference Patterns On A Water Surface
Interference occurs when waves from different sources overlap, creating new patterns. On a water surface, this can be easily observed when ripples from different points meet, forming distinctive interference patterns. These patterns can show us how waves combine in different ways, either reinforcing each other or canceling out.

Studying these patterns helps us understand wave behavior in a simple, visual way. It also allows us to explore important concepts, like the relationship between wave phase and the effects of multiple sources. This task offers a hands-on approach to learning about wave interactions and their real-world applications, making it an interesting and engaging way to dive into wave physics.

<br><hr><br>

## 1. Theory and Mathematical Formulation
When a point source generates ripples on a water surface, it emits a circular wave that propagates outward from the source. At any location on the water surface, the vertical displacement (height) of the water due to this wave at a given time can be described by a mathematical wave function.

A circular wave on the water surface, emanating from a point source located at $(x_0, y_0)$, can be described by the Single Disturbance equation:

$$
\eta(x, y, t) = \frac{A}{\sqrt{r}} \cdot \cos\left(kr - \omega t + \phi\right)
$$
 
##### Where:

- **$\eta(\vec{r}, t)$** is the displacement of the water surface at point $(x, y)$ and time $t$
- **$A$** is the amplitude of the wave
- **$k = \frac{2\pi}{\lambda}$** is the wave number, related to the wavelength $\lambda$
- **$\omega = 2\pi f$** is the angular frequency, related to the frequency $f$
- **$r = \sqrt{(x - x_0)^2 + (y - y_0)^2}$** is the distance from the source to the point $(x, y)$
- **$\phi$** is the initial phase

#### Explanation of Terms:
Amplitude $A$: Controls how "tall" the wave is. Physically, it represents the energy or intensity of the wave. Larger amplitude means higher crests and deeper troughs.

Distance $r$: As waves spread out from a point source, the distance from the source to the point of observation affects how the wave arrives there — both in timing (due to finite speed) and in shape (since the wavefront is expanding).

Wave Number $k$: Indicates how rapidly the wave oscillates in space. Smaller wavelengths result in larger values of $k$, meaning more oscillations over a given distance.

Angular Frequency $\omega$: Describes how rapidly the wave oscillates in time. Higher frequencies (shorter periods) mean faster oscillations.

Phase $\phi$: This is the initial “starting angle” of the wave. Adjusting this allows for modeling phase differences between waves, which is crucial in interference analysis.

<br><hr><br>

## 2. Python Simulation

<div style="text-align: center;">
  <a href="https://pythonsimulation-xaase6arhfiz4bqu3hcjou.streamlit.app/" target="_blank">
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

<br><hr><br>

## 3. Conclusion
In conclusion, understanding wave interference patterns on water surfaces provides insight into wave interactions, showcasing both constructive and destructive interference. This study enhances our comprehension of wave behavior and its real-world applications in various fields, such as physics and engineering. By utilizing simulations, we can visually explore how waves emitted from point sources interact, offering a practical method for analyzing complex wave phenomena. This task contributes to a deeper understanding of the principles of superposition, wave behavior, and their effects on different systems.

<br>
