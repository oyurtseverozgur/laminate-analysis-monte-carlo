# laminate-analysis-monte-carlo
# Design-dependent weight saving governs the life-cycle carbon balance of carbon-fibre composite substitution for aerospace aluminium

(https://doi.org/10.5281/zenodo.24437369)

This repository contains the Python implementation, index derivation, and Monte Carlo simulation model used in the manuscript submitted to the **Journal of Cleaner Production** (Elsevier). 

The code evaluates the design-dependent weight saving and life-cycle carbon balance of substituting aerospace aluminium (2024-T3 and 7075-T6) with carbon-fibre reinforced polymers (CFRP).

## 📁 Repository Contents

*   **`laminate.py`**: Implementation of classical laminate analysis and failure criteria for composite materials.
*   **`derive_w.py`**: Derivation of the weight-saving index and break-even design strain (ε*).
*   **`model4.py`**: The Monte Carlo simulation model, including the corrected Iman–Conover correlation step (which preserves design criteria and alloy labels).
*   **`reproduce_revision.py`**: The main execution script that runs the complete analysis and generates the data for the manuscript.
*   **`make_figures.py`**: Script to generate the figures and tables presented in the paper.
*   **`results_revision.json`**: The output data containing the simulation results. 
*   **`README.md`**: This file.

## ⚙️ Requirements

The code is written in Python 3. Required libraries can be installed via pip:
```bash
pip install numpy scipy pandas matplotlib
