# Solar System Simulation Using Python

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)
![License](https://img.shields.io/badge/License-MIT-green)

*A simple computational simulation of the Solar System built with Python and Matplotlib.*

## Overview

This project presents a simple two-dimensional simulation of the Solar System developed using Python in a Jupyter Notebook environment. The simulation visualizes the Sun and the eight planets orbiting around it while demonstrating the application of mathematical concepts, scientific visualization, and animation techniques.

The primary objective of this project is educational rather than astronomical accuracy. It was created to explore how mathematical models can be translated into interactive visualizations using Python and to strengthen fundamental programming skills through a practical application.

---

## Objectives

This project was developed to:

- Learn the fundamentals of scientific computing with Python.
- Understand how trigonometric functions can model orbital motion.
- Explore animation techniques using Matplotlib.
- Practice numerical computation with NumPy.
- Build a structured and reproducible simulation in Jupyter Notebook.

---

## Technologies Used

The project is built using the following libraries:

- Python 3
- NumPy
- Matplotlib
- IPython Display
- Jupyter Notebook

Install the required dependencies with:

```bash
pip install numpy matplotlib notebook
```

---

## Running the Project

1. Launch Jupyter Notebook or JupyterLab.
2. Open `Solar_System_Simulation.ipynb`.
3. Run all notebook cells sequentially.
4. Wait for the animation to finish rendering.
5. The simulation will be displayed directly inside the notebook.

---

## Project Structure

The notebook is organized into several sections:

- Library imports
- Simulation parameters
- Planet data initialization
- Orbital position calculations
- Animation setup
- Rendering the simulation

This modular structure makes the code easier to understand, modify, and extend.

---

## Methodology

Each planet's position is calculated using the parametric equations of a circle based on sine and cosine functions. During every animation frame, new coordinates are computed according to the simulated time, creating the appearance of continuous orbital motion around the Sun.

To keep the simulation lightweight and easy to understand, orbital distances, planetary sizes, and revolution speeds are simplified rather than based on real astronomical measurements. This approach allows the project to focus on computational concepts while remaining visually intuitive.

---

## Features

The simulation includes:

- The Sun positioned at the center of the Solar System.
- Eight planets with individual colors.
- Animated planetary orbits.
- Orbital trails for each planet.
- Planet labels.
- A simulation timeline representing approximately 230 million years.

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Scientific computing with NumPy.
- Data visualization using Matplotlib.
- Creating animations with `FuncAnimation`.
- Applying trigonometric functions to simulate motion.
- Organizing Python projects in Jupyter Notebook.
- Translating mathematical concepts into computational models.

Beyond programming, this project also strengthened my understanding of how visualization can be used to communicate scientific concepts effectively.

---

## Future Improvements

Several enhancements can be implemented in future versions, including:

- Elliptical orbits based on Kepler's laws.
- Real astronomical data for planetary size, distance, and orbital periods.
- Gravitational interactions between celestial bodies.
- Natural satellites and asteroid belts.
- Interactive controls for zooming and simulation speed.
- Integration with the REBOUND N-body simulation library for more realistic physics.

---

## Conclusion

This project represents an early exploration of scientific visualization and computational simulation using Python. While the current implementation intentionally simplifies many aspects of celestial mechanics, it demonstrates the fundamental relationship between mathematics, programming, and visualization.

Developing this simulation allowed me to strengthen my Python programming skills while gaining a deeper appreciation for how computational methods can be used to model real-world phenomena. It also serves as a foundation for future projects involving numerical simulation, data visualization, and scientific computing.
