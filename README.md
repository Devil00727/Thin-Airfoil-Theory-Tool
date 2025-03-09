# Thin Airfoil Theory Tool

## Overview
This project focuses on implementing **Thin Airfoil Theory** through a computational tool that predicts airfoil performance. The tool enables efficient aerodynamic analysis by reducing computational costs while maintaining high accuracy compared to CFD simulations.

## Project Details
- **Domain**: Algorithm Development, Aerodynamics
- **Duration**: February 2024 - March 2024
- **Guide**: Prof. Dhwanil Shukla
- **Tech Stack**: Python, NumPy, Matplotlib, SciPy, Pandas

## Key Features
- **Computational Efficiency**: Reduces analysis time and resource consumption.
- **Aerodynamic Analysis**:
  - Plots airfoil **camber line** and its **slope**.
  - Computes **lift coefficient (Cl)** and **moment coefficient (Cm)**.
  - Generates **vector field plots** to visualize airfoil circulation.
  - Computes **circulation through line integrals** and **circulation distribution**.
- **Validation**: Shows a **0.5% disparity** between the tool’s predictions and CFD simulation results.

## Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/Devil00727/Thin-Airfoil-Theory-Tool.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Thin_aifoil_theory_tool.ipynb
   ```

## Usage
- The notebook provides step-by-step implementation of thin airfoil theory.
- Modify airfoil parameters and angles of attack to observe aerodynamic effects.
- Compare results with CFD simulations for validation.

## Results
- The tool successfully replicates theoretical predictions for airfoil performance.
- **Coefficient of Lift (Cl) vs. Angle of Attack (α)** aligns with CFD results.
- **Circulation Computation** via different methods yields consistent results.
- **Vector Field Visualization** enhances understanding of airflow patterns.

## License
This project is open-source and available under the **MIT License**.

---
For more details, refer to `Thin_aifoil_theory_tool.ipynb` and `Report.pdf`.

