## Accurate boundary-integral formulations for the calculation of electrostatic forces with an implicit-solvent model

Codes for paper on different formulations for electrostatics forces calculation with a boundary element method. Collaboration between Ian Addison-Smith, Horacio V. Guzman and Christopher D. Cooper. Here you'll find:

* `force_simulations.ipynb`, `force_plots.ipynb`: Jupyter notebooks files to reproduce the results of the paper. These use the PBJ software: https://github.com/bem4solvation/pbj and `pqrs` folder for pqr files
* `APBS_script.ipynb`: Jupyter notebook examples for APBS 1.4.1 use for force calculations examples 
* `Apbs_simulation.in`, `Apbs_template.in` and `apbs_tools.py` to run APBS within the jupyter notebook
* `results`, `results_PBJ`: Txt results for simulations
* `figures`: Figures obtained in the simulations (Not all were used)
* `msh_sphere`: plots on .msh format for phi, d_phi, P_normal and the force terms in the energy functional variation approach
