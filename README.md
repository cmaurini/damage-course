# Gradient damage models as phase-field models of brittle fracture

We give here exemples of the numerical solution of the quasi-static evolution problem for gradient damage models, and show how they can be used to solve brittle fracture problems.

The codes depend on FEniCS 2018.1.0. To run it we suggest to follow one of the following solutions:
 - Use Google colab Notebooks
 - Use Docker containers provided by FEniCS developers, see here: https://fenicsproject.org/download/

You can find further informations about this model here:
- Marigo, J.-J., Maurini, C., & Pham, K. (2016). An overview of the modelling of fracture by gradient damage models. Meccanica, 1–22. https://doi.org/10.1007/s11012-016-0538

# Content

- `notebook/VarFrac.ipynb`: A basic commented example for the finite element implementation of the phase-field models of fracture using FEniCS. Open and play with the notebook in google colab: https://colab.research.google.com/github/cmaurini/damage-course/blob/master/notebook/VarFrac.ipynb

- `notebook/VI.ipynb`: A simple example on how to solve a Variational Inequality in FEniCS. Open and play with the notebook in google colab: https://colab.research.google.com/github/cmaurini/damage-course/blob/master/notebook/VI.ipynb

- `notebook/Inclusion.ipynb`: The numerical solution of a nontrivial fracture problem using the phase-field approach. Open and play with the notebook in google colab: https://colab.research.google.com/github/cmaurini/damage-course/blob/master/notebook/Inclusion.ipynb

- `notebook/VI-notes.ipynb`: Some notes on variational inequalities. Open and play with the notebook in google colab: https://colab.research.google.com/github/cmaurini/damage-course/blob/master/notebook/VI-notes.ipynb

The code is currently based on the use of FEniCS 2018.1 and python3

# Author

Corrado Maurini, corrado.maurini@upmc.fr
