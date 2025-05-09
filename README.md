# Basic Sounding Rocket Simulation using Python

**Project made as part of assessment for Python Lab course**

This repository contains a Python-based simulation of a sounding rocket's flight. It models key physical forces such as thrust, drag, and gravity to simulate the rocket's ascent and descent, providing visual insights into altitude, velocity, and acceleration over time.

## Overview  
This project simulates the flight of a sounding rocket, modeling critical aspects such as thrust, drag, gravity, and air density variations. Using numerical integration techniques, the simulation tracks the rocket's altitude, velocity, and acceleration, producing visual plots to analyze flight performance.  
![image](https://github.com/user-attachments/assets/c67a97d9-b664-4a8f-a5b6-626a1b6a2881)
[Source: https://www.jpl.nasa.gov/infographics/what-is-a-sounding-rocket/]

## Features  
- **Dynamic Forces:** Simulates thrust, drag (varying with altitude and velocity), and gravity.  
- **Air Density Variation:** Models exponential decrease in air density with altitude.  
- **Data Visualization:** Generates plots for altitude, velocity, acceleration, and forces acting on the rocket throughout the flight.  
- **Realistic Parameters:** Rocket characteristics (mass, drag coefficient, thrust) are inspired by a real-world sounding rocket.  

## How It Works  
1. **Initialization:** Define rocket properties (mass, thrust, diameter, etc.) and environmental constants (gravity, air density).  
2. **Numerical Integration:** Iteratively compute forces and update the rocket's state over time.  
3. **Simulation Termination:** The simulation ends when the rocket returns to the ground.  
4. **Visualization:** Plots of altitude, velocity, acceleration, and forces over time are generated for analysis.  

## Code Structure  
- **Rocket Model:** A class-based Python implementation defining rocket physics, forces, and integration.  
- **Simulation:** A loop iteratively calculates flight metrics until termination.  
- **Visualization:** Uses Matplotlib to plot results.  
