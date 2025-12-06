# Projectile Motion Simulator (MATLAB)

A MATLAB project that simulates and visualises the motion of a projectile using SUVAT equations.  
Developed for the ENGFF003 – Computer Methods Major Project.

---

## Overview
This project models the trajectory of a projectile launched at a given height and velocity, with and without obstacles.  
The simulation calculates the projectile’s motion, animates its flight, and provides detailed information about its position, velocity, and time throughout the trajectory.

---

## Scenarios
The simulator supports two scenarios:

### Scenario 1 – No Obstacles
- User inputs:
  - Launch height
  - Initial velocity (magnitude and direction)
- The projectile motion is simulated until it hits the ground
- The full trajectory is plotted
- Time of flight and total horizontal distance are displayed

### Scenario 2 – Wall Obstacle
- User inputs:
  - Launch height
  - Wall height
  - Distance to the wall
  - Initial velocity (magnitude and direction)
- The simulation ends when the projectile hits either:
  - The ground, or
  - The wall
- The program reports:
  - Time of flight
  - Horizontal distance traveled (if ground is hit), or
  - Height of impact on the wall

---

## Features
- Physics-based simulation using SUVAT equations
- No air resistance (ideal projectile motion)
- Trajectory plotting
- Animated flight of the projectile
- Graphical User Interface (GUI) with:
  - Slider to move along the trajectory after animation
  - Highlighted point on the graph
  - Display of:
    - Horizontal and vertical position
    - Time since launch
    - Velocity magnitude and direction



---

## How to run
1. Open the `.mlapp` file in MATLAB
2. Run the script or app
3. Enter the required inputs through the GUI
4. Select a scenario
5. Watch the animation and explore the trajectory using the slider


---

## Learning Outcomes
- Applying kinematic equations in code
- Building simulations and animations in MATLAB
- Creating interactive GUIs
- Writing readable, well-documented code
- Implementing error handling and input validation

