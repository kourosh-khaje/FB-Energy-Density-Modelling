# FB Energy-Density Modelling 

## Overview

This open-source script provides a complete framework for estimating practical energy densities for vanadium-based and gas–liquid hybrid flow batteries. The code couples a full Butler–Volmer + mass-transport model (liquid side) with a simplified Nernst model (gas side) and produces four comparison tables plus an interactive 3-D bar chart.
https://doi.org/10.1016/j.seta.2026.104887

## Features

• Ready-to-run – only numpy, pandas, scipy, matplotlib required

• Compares “standard” (2 M) and “mixed-acid” (2.5 M) vanadium chemistries

• Validates against literature values (error column automatically generated)

• Outputs Markdown tables that can be pasted directly into papers or reports


## Methodology

Coupled electrochemical model: Butler–Volmer kinetics with concentration-dependent mass-transport limitations for the liquid-phase vanadium reactions, plus Nernst-equilibrium treatment of the gas-side reactant (O₂ or H₂). Energy density is computed from the vanadium concentration, operating SOC window, and tank volume, then benchmarked against published experimental data to generate percent-error columns.

## Applications

• Research institutions: Benchmark new electrolyte formulations and membrane materials

• Industry stakeholders: Screen chemistries for MW-scale system design and cost-down studies

• Policy makers: Compare realistic energy densities for long-duration storage tech selection

• Investors: Risk-return evaluation via validated performance gaps vs. incumbent batteries


## Contributing

We welcome contributions! Please see our Contributing Guide for:

• Code style guidelines

• Testing procedures

• Pull request process


## License

This project is licensed under the MIT License – see the LICENSE file for details.

## Citation

If you use this code in an academic work, please cite:

Khaje, K. (2026). FB Energy-Density Modeling (v1.0). https://github.com/kourosh-khaje/Flow-Battery-Energy-Density-Modelling.git

## Contact

For questions or suggestions:

• Create an Issue

• Email: kourosh.khaje@outlook.com

• Discussion forum: GitHub Discussions



