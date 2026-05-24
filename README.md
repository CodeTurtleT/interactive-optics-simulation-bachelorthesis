# Interactive Optics Simulation Tool 🔬💻

## About the Project
This repository contains an interactive Python simulation developed as part of my B.Sc. Thesis in the Laser Technology department at the Fraunhofer Institute for Applied Optics and Precision Engineering (IOF).

**Supervisors:** Dr. Matthias Goy & Paul Böttner  
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

## Repository Files
* `second_lens.ipynb` - The main Jupyter Notebook containing the interactive simulation and the optical calculations.
* `requirements.txt` - List of Python dependencies required to run the simulation seamlessly.
* `README.md` - Project documentation.

## Usage
1. Install the required dependencies via `pip install -r requirements.txt`.
2. Open and run all cells in `second_lens.ipynb` to launch the interactive widget. 
3. Use the sliders to dynamically adjust the optical parameters and immediately observe the resulting changes in the simulated beam profile and the generated data tables.
