# Electrochemical Activity on MPEA

The repository contains the datasets and scripts necessary to reproduce the results in the paper:

```bibtex
@article{mpea,
    author = {Yuwono, Jodie A and Li, Xinyu and Dole{\v{z}}al, Tyler D and Samin, Adib J and Shi, Javen Qinfeng and Li, Zhipeng and Birbilis, Nick},
    title = {A Computational Approach for Mapping Electrochemical Activity of Multi-Principal Element Alloys},
    journal = {npj Materials Degradation},
    year = {2023}
}
```

We acknowledge the extensive use and modifications based on the following repositories:
- [GASpy](https://github.com/ulissigroup/GASpy)
- [GASpy_regressions](https://github.com/ulissigroup/GASpy_regressions)
- [GP-representations](https://github.com/UON-comp-chem/GP-representations)

# Manifest
*  `data/` contains the datasets for adsorption energy and vacancy energy.
*  `catlearn/` contains various functions used in this study. Most of the .py files here are copied from [GP-representations](https://github.com/UON-comp-chem/GP-representations)
* `catlearn/coordination_features.py` was copied from [GASpy_regressions](https://github.com/ulissigroup/GASpy_regressions). Credit goes to its developers.
* `atoms_operators.py` is a Python code that contains various functions for an ASE object. Credit goes to the [GASpy](https://github.com/ulissigroup/GASpy) developers.
* `gaspymongo.py` is a Python code that contains functions to read structures in the data folder. This code was copied from [GASpy](https://github.com/ulissigroup/GASpy). Credit goes to the GASpy developers and the original author, Prof. John Kitchin.
* `adsorption_energy.ipynb`  is a Jupyter notebook script used to reproduce the machine learning prediction of adsorption energies.
* `vacancy_energy.ipynb`  is a Jupyter notebook script used to reproduce the machine learning prediction of vacancy energies.
