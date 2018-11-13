# Gradient damage models as phase-field models of brittle fracture

We give here exemples of the numerical solution of the quasi-static evolution problem for gradient damage models, and show how they can be used to solve brittle fracture problems.

The codes depend on FEniCS 2018.1.0. To run it we suggest to follow one of the following solutions:
 - Use Google colab Notebooks
 - Use Docker containers provided by FEniCS developers, see here: https://fenicsproject.org/download/

You can find further informations about this model here:
- Marigo, J.-J., Maurini, C., & Pham, K. (2016). An overview of the modelling of fracture by gradient damage models. Meccanica, 1–22. https://doi.org/10.1007/s11012-016-0538


# Syllabus - 5AG08 Damage and fracture - Corrado Maurini

1. Introduction
    1. Variational fracture and gradient damage models as its variational approximation. 
    2. Examples: Thermal shock and others. 
2. Variational inequalities
    1. An example with one degree of freedom
    2. Karush-Kuhn-Ticker conditions for the minimization of a functional under unilateral constraint (without proof)
    3. Numerical VI solvers. Example and notebook.
3. Local damage model
    1. Variational formulation
    2. Homogenous solutions
    3. Issue about localization with zero energy
    4. Numerical illustration: notebook
4. Gradient damage models 
    1. Variational formulation
    2. Homogenous solution --> see local model
    3. Localised solutions
    4. Numerical implementation 
    5. The key properties of the gradient damage models as phase field model of fracture
    6. Applications and overview of recent results
