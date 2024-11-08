# README - Capacitron Duel: Interactive Reflex and Speed Game

## Game Description

**Capacitron Duel** is a two-player reflex and speed game inspired by classic arcade games. The rules are simple: it’s a head-to-head test of reflexes and precision.

## Objective of the Game

Two players compete, each using a sensor. The game continues until one player reaches **9 points**, concluding the match. Here's how it works:
- **Red LED**: When lit, players must avoid touching their sensor to prevent losing a point.
- **Green LEDs**: After a random delay, the green LEDs light up, and the first player to touch their sensor scores a point.

## Project Stages

This project follows a prototyping methodology to efficiently design and test the game. Key development stages include:

### Conceptualization and Modeling
- **Partquest**: Used for electrical schematic modeling.
- **COMSOL**: Simulates physical forces and analyzes electrodes to optimize performance.
- **Preliminary Testing**: A prototype with a single electrode on a board validates the detection model.

### Final Design
- **KiCad**: PCB design for the final circuit.
- **Autodesk Inventor**: 3D modeling and part preparation for printing.
- **STM32 CubeIDE**: Programming ST boards to handle game functions.
- **Visual Studio**: Organizes and structures the code for clarity and maintainability.

## Resources

The following tools were essential in the development of **Capacitron Duel**:

### Modeling and Simulation
- **COMSOL**: Simulates physical forces on electrodes.
- **Partquest**: Electrical schematic modeling and simulation.
- **Draw.io**: Creates conceptual diagrams.

### Design and Prototyping
- **KiCad**: For PCB design.
- **Autodesk Inventor**: For 3D part modeling and printing preparation.

### Software Development
- **STM32 CubeIDE**: For coding on ST boards.
- **Visual Studio**: For code formatting and project management.
