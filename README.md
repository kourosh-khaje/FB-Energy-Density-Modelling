# Flow-Battery Energy-Density Calculator

A short, self-contained Python script that estimates practical energy densities for vanadium‐based and gas–liquid hybrid flow batteries. The code couples a full Butler–Volmer + mass-transport model (liquid side) with a simplified Nernst model (gas side) and produces four comparison tables plus an interactive 3-D bar chart.

## Features
- Ready-to-run – only `numpy`, `pandas`, `scipy`, `matplotlib` required  
- Compares “standard” (2 M) and “mixed-acid” (2.5 M) vanadium chemistries  
- Validates against literature values (error column automatically generated)  
- Outputs Markdown tables that can be pasted directly into papers or reports

Citation

If you use this code in an academic work, please cite:
Khaje, K. (2026). Flow-Battery Energy-Density Calculator (v1.0).
https://github.com/kourosh-khaje/Flow-Battery-Energy-Density-Estimation.git
