# 2D Particle Simulator Grid in C#
C# implementation of a 2D Particle Simulator. The simulator is designed to model and visualize particle behavior on a grid-based environment. It features a dynamic simulation grid where particles follow specific movement rules, creating interesting patterns and interactions.

# Key Features
- Dynamic Grid: Utilizes a grid system (customizable in size, defaulting to 800x600) to simulate particle movements. Each grid cell can be in one of three states: on (active particle), off (empty), or wall (obstacle).
- Efficient Simulation: Employs a linked list to track active particles, significantly reducing computational overhead by focusing only on cells that are in the 'on' state.
- Particle Movement Logic: Particles within the grid follow a defined set of rules: they fall downwards, move diagonally if blocked directly below, and stack if unable to move.
- Double Buffering Mechanism: Implements double buffering to ensure smooth transitions and state updates during the simulation.
- Scalable Design: Designed to be adaptable to various grid sizes, making it suitable for different scales of simulations.
- Headless Operation: Initially developed to run without a UI, focusing on the simulation logic and data output, with potential for future UI integration (e.g., using SDL for visualization).

# Project Status
The project is currently in a developmental stage, focusing on refining the core simulation logic and optimizing performance. Future enhancements will include UI development for visualization and extended simulation features.

# Getting Started
Instructions for cloning the repository, setting up the development environment, and running the simulator are provided in the documentation.
