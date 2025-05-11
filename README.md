# Procedural Sun Shader

A GLSL shader that simulates the look and feel of a blazing sun using layered procedural effects. This project demonstrates how multiple shaders can be combined to create a compelling, animated Sun with a core disc, solar corona, and dynamic flares.

## Demo

[![Watch the Demo]]https://youtu.be/2O4LYdh_220

---

## Overview

This project visualizes a stylized sun using a combination of GLSL fragment and vertex shaders. It showcases techniques such as time based animation, procedural noise, radial falloff, and additive blending to create a layered, glowing effect.

---

## Features

- **Emissive Core Disc**  
  A smooth, bright inner sun created with a radial gradient and soft edges.

- **Animated Solar Corona**  
  Wispy turbulence built with layered noise and animated over time to simulate convection and plasma motion.

- **Procedural Solar Flares**  
  Sharp, ray-like bursts rendered using polar coordinate math and sine functions, rotating and flickering for added intensity.


---

## 🛠️ Technologies Used

- **GLSL (OpenGL Shading Language)** – for real-time fragment shader programming.
- **glman** – lightweight shader viewer used for prototyping and rendering.
- **Procedural Techniques** – including `smoothstep`, `sin/cos`, `length()`, and value noise.
- **Time-Based Animation** – enables dynamic corona flicker and flare rotation.


---

## 📌 Learning Outcomes

This project helped me strengthen my understanding of:

- Layering multiple fragment shaders using additive blending
- Procedural noise and texture generation in GLSL
- Using time as a variable for animation
- Working in polar and UV coordinate spaces
- Creating modular and composable visual effects

