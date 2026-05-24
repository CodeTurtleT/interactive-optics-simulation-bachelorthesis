# Interactive Optics Simulation Tool 🔬💻

## About the Project
This repository contains an interactive Python simulation developed as part of my B.Sc. Thesis in the Laser Technology department at the Fraunhofer Institute for Applied Optics and Precision Engineering (IOF).

**Supervisors:**  Paul Böttner  
**Institution:** Fraunhofer IOF, Jena  

The core of this project is a simulation tool designed to analyze variable divergence adjustment in optomechanical setups. It calculates and visualizes Gaussian beam propagation and the effective focal length of a two-lens system.

## Key Features
* **Interactive UI:** Built-in sliders (`ipywidgets`) for dynamic, real-time adjustments of physical parameters such as free space length ($l$), lens distance ($d$), and focal length ($F_2$).
* **Real-time Beam Plotting:** Visual comparison between the original beam waist and the newly adjusted beam waist $w(z)$ along the propagation axis (up to 100 meters).
* **Automated Data Tables:** Generates clean, formatted tables summarizing optical system parameters (e.g., effective focal length, divergence angle $\theta$) and exact beam radii at specific target distances (1m, 10m, 100m).

## Tech Stack
* **Python** * **Matplotlib & ipywidgets** for the interactive interface and plotting
* **NumPy** for the mathematical modeling of the optical beam physics
* **Tabulate** for structured, readable terminal data outputs

## Repository Structure
* `/code` - The Jupyter Notebook (`second_lens.ipynb`) containing the interactive simulation.
* `/demo` - Screenshots of the interactive dashboard and data tables in action.

## Usage
Simply run all cells in the Jupyter Notebook to launch the interactive widget. Use the sliders to dynamically adjust the optical parameters and immediately observe the resulting changes in the simulated beam profile and the generated data tables.
