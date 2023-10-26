# Electrochemical Activity on MPEA

The repository contains the datasets and scripts used to reproduce the results in the paper:

```bibtex
@article{mpea,
    author = {Yuwono, Jodie A and Li, Xinyu and Dole{\v{z}}al, Tyler D and Samin, Adib J and Shi, Javen Qinfeng and Li, Zhipeng and Birbilis, Nick},
    title = {A Computational Approach for Mapping Electrochemical Activity of Multi-Principal Element Alloys},
    journal = {npj Materials Degradation},
    year = {2023}
}
```

We acknowledge the heavy use and modifications based on the floowing repos:
- [GASpy](https://github.com/ulissigroup/GASpy)
- [GASpy_regressions](https://github.com/ulissigroup/GASpy_regressions)
- [GP-representations](https://github.com/UON-comp-chem/GP-representations)

# Manifest
*  `data/` contains the adsorption energy and vacancy energy data sets.
*  `catlearn/` contains various functions used this study. Most of the `.py` files here are copied from [[GP-representations](https://github.com/UON-comp-chem/GP-representations)]
* `catlearn/coordination_features.py` was copied from [[GASpy_regressions](https://github.com/ulissigroup/GASpy_regressions)]. Credit goes to its developers.
* `atoms_operators.py` is a Python code that contains various functions for a ASE object. Credit goes to the [[GASpy](https://github.com/ulissigroup/GASpy)] developers.
* `gaspymongo.py` is a Python code that contains functions to read structures in the data folder. This code was copied from [[GASpy](https://github.com/ulissigroup/GASpy)]. Credit goes to the GASpy developers and the original author, Prof. John Kitchin.
* `adsorption_energy.ipynb`  is a Jupyter notebook script used to reproduce the ML prediction of adsorption energies.
* `vacancy_energy.ipynb`  is a Jupyter notebook script used to reproduce the ML prediction of vacancy energies.
