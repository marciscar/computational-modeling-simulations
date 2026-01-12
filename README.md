## Computational modeling and simulation project (PhD research)

This repository contains Python code and notebooks developed during my PhD research, focused on the numerical modeling and simulation of a complex dynamical system governed by coupled differential equations.

The goal of this project was not to build a production-ready software package, but to explore system behavior across different regimes, study the impact of model assumptions, and analyze high-dimensional outputs through iterative computational experiments.

---

### Problem overview

The system under study involves multiple interacting components with non-trivial dynamics that cannot be solved analytically. Understanding its behavior requires:

- Designing a numerical model
- Solving coupled ODEs across different parameter regimes
- Exploring large parameter spaces
- Analyzing and visualizing emergent behavior

The emphasis of this work is on the modeling approach and computational workflow rather than on domain-specific theoretical details.

---

### What this repository shows

This repository illustrates how I approach complex modeling problems using code:

- Translating an ill-defined research question into a concrete computational model
- Implementing numerical solvers and simulation pipelines in Python
- Running parameter scans to explore system behavior
- Analyzing and visualizing simulation outputs to extract trends and validate assumptions
- Iteratively refining the model based on results

The code reflects an exploratory research workflow and prioritizes clarity of logic and experimentation over software engineering completeness.

---

### Repository structure

The repository contains three main notebooks, each addressing a different aspect of the modeling and numerical analysis. They can be read independently, depending on the part of the workflow of interest.

---

#### [Freeze_out_and_washout.ipynb](Freeze_out_and_washout.ipynb)    
This notebook focuses on the numerical behavior of the coupled equations in the freeze-out regime, where interaction rates become inefficient compared to the expansion of the system.

It includes:
- definition of the coupled system of equations  
- numerical integration using SciPy solvers  
- visualization of freeze-out dynamics  
- comparison of different freeze-out scenarios  
- treatment of washout terms and their numerical impact  

---

#### [Asymmetry_generation.ipynb](Asymmetry_generation.ipynb)  
This notebook explores the generation of an asymmetry through competing dynamical processes.

It includes:
- importing and adapting thermally averaged interaction rates  
- modeling of source terms responsible for asymmetry generation  
- analysis of competing processes that create and erase asymmetries  
- numerical integration over the relevant parameter and temperature ranges  
- large parameter space scans  
- visualizations highlighting regions of successful asymmetry generation  

---

#### [Full_regime_integrations_and_plots.ipynb](Full_regime_integrations_and_plots.ipynb)  
This notebook provides an end-to-end example combining multiple dynamical regimes.

It illustrates:
- how the system is adapted in different regimes depending on active interactions  
- the complete numerical evolution of the system variables  
- final plots summarizing the full simulation and analysis pipeline  

---

### Notes

- This code was developed for research purposes and reflects an exploratory workflow.
- It is not intended as a polished library or production system.
- The focus is on modeling choices, numerical experimentation, and analysis rather than on performance optimization or packaging.
