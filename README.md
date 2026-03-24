# Techno-Economic Modeling of Green Hydrogen Production

## Project Overview
This repository contains a computational model developed to simulate the efficiency and economic feasibility of industrial-scale Green Hydrogen production via water electrolysis. The project bridges the gap between theoretical electrochemistry and industrial process simulation.

## Key Features
* **Mass Balance Modeling:** Python-based simulation using **Faraday's Law of Electrolysis** to predict H2 yield.
* **Energy Analytics:** Calculation of **Specific Energy Consumption (SEC)** and cost-to-production ratios using **NumPy and Pandas**.
* **Thermodynamic Validation:** Validation of energy requirements in **DWSIM** using the **Peng-Robinson (PR78)** Equation of State.

## Governing Physics
The production yield is governed by Faraday’s First Law:
$$m = \frac{I \cdot t \cdot M}{n \cdot F}$$

* **m**: Mass of Hydrogen (g)
* **I**: Applied Current (A)
* **M**: Molar Mass of H2 (2.016 g/mol)
* **n**: Valence electrons (2)
* **F**: Faraday Constant (96,485 C/mol)

## Simulation Results & Validation
* **SEC Analysis:** Calculated a Specific Energy Consumption of approximately **71 kWh/kg** at 75% system efficiency.
* **DWSIM Validation:** Steady-state simulation in DWSIM confirmed a theoretical **Heat Duty of ~15.9 MW** for a water feed rate of 1 kg/s at 298.15 K.
* **Economic Trade-offs:** Identified the optimal current density to balance high production rates with energy efficiency.

## Repository Contents
* `H2_production_project.ipynb`: Python computational model and data visualization.
* `Green_H2_Model.dwxmz`: DWSIM process simulation file.

## Technical Proficiency
* **Languages:** Python (NumPy, Pandas, Matplotlib)
* **Tools:** DWSIM, Google Colab, GitHub
