# PhD Numerical Code – Selected Jupyter Notebooks

This folder contains three Jupyter notebooks that showcase the numerical work I developed during my PhD.  
The notebooks illustrate how the Boltzmann equations for particle abundances and asymmetries were modelled, simplified across different temperature regimes, and solved numerically using Python and SciPy’s ODE solvers.

For this purpose, I have included only the notebooks themselves, not the full set of auxiliary files and modules that the complete project depends on.  
The idea is to make it easy to read and review the code and the numerical workflow.  
If you would like to run the notebooks, I can provide the full set of files and inputs on request.

---

## 1. Freeze_out_and_washout.ipynb  
This notebook focuses on the behaviour of the Boltzmann equations around freeze-out, where interaction rates become inefficient compared to the Hubble expansion.  
It shows:
- definition of the coupled system of equations  
- integration with SciPy solvers and visualisation of freeze-out dynamics  
- comparison of different freeze-out scenarios
- treatment of washout terms and their numerical impact  

---

## 2. Asymmetry_generation.ipynb  
This notebook explores the generation of the dark matter asymmetry.  
It includes:
- importing and adapting the thermally averaged cross sections of washout processes
- modelling of CP-violating source terms  
- analysis of competing processes that create and erase asymmetries  
- numerical integration of the system across the relevant temperature window  
- large parameter space scans
- plots illustrating the parameter space for successful asymmetry generation  


---

## 3. Full_regime_integrations_and_plots.ipynb  
This notebook provides an end-to-end example combining several temperature regimes.  
It illustrates:
- how the system is adapted in each regime depending on which interactions are active  
- the complete numerical evolution of abundances and asymmetries  
- final plots summarising the full solution pipeline  

