# Interactive Optics Simulation Tool 🔬💻

## About the Project
This repository contains an interactive Python simulation developed as part of my B.Sc. Thesis in the Laser Technology department at the Fraunhofer Institute for Applied Optics and Precision Engineering (IOF).

**Supervisors:**  Paul Böttner  
**Institution:** Fraunhofer IOF, Jena  

The core of this project is an interactive visualization tool designed to simulate and analyze variable divergence adjustment in optomechanical setups. It was specifically built to present complex optical parameter changes in real-time, allowing users to intuitively explore the system's behavior.

## Key Features
* **Interactive UI:** Built-in sliders (widgets) for dynamic, real-time adjustments of physical parameters (e.g., lens distances, beam divergence angles).
* **Real-time Plotting:** Instantaneous visual feedback on how parameter shifts affect the optical system and beam propagation.
* **Physics Engine:** Under-the-hood mathematical modeling of optical elements and laser beam physics.

## Tech Stack
* **Python** * **Matplotlib (Widgets)** for the interactive slider interface and real-time rendering
* **NumPy** for rapid matrix and array computations underlying the optical model

## Repository Structure
* `/src` - The main Python scripts containing the simulation logic and interactive UI.
* `/demo` - Screenshots and examples of the interactive dashboard in action.

## Usage
Simply run the main script to launch the interactive matplotlib window. Use the sliders at the bottom of the figure to dynamically adjust the optical parameters and observe the resulting changes in the simulated beam profile.
