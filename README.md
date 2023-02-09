# Hyper-Elastic Geometrically Nonlinear Inverse 3D-FEM Truss Analyses Based on VaReS

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/KlausBSautter/Find_Reference_Truss_3D/HEAD)

Find the unknown reference configuration for geometrically and materially nonlinear and linear truss structures. Try the examples online via the given *binder* link, or clone this repository to your local machine. The examples are ordered according to the paper provided at the end.

You are welcome to contact me for further assistance.


## Necessary Python Packages

You need to install `numpy` and `matplotlib`.

- In the Jupyter Notebook:
```
import sys
!{sys.executable} -m pip install numpy
!{sys.executable} -m pip install matplotlib
```

- In the Python console:
```
pip install numpy matplotlib
```

## Create Input Data

Input data can either be created manually via the Python code, or with the help of [Kratos Multiphysics](https://github.com/KratosMultiphysics/Kratos) and the CAD system [GiD](https://www.gidsimulation.com/). 

## Cite Me
Klaus Bernd Sautter, Kai-Uwe Bletzinger, Hyper-Elastic Geometrically Nonlinear Inverse 3D-FEM Truss Analyses Based on VaReS, Advances in Civil Engineering (2022)
http://dx.doi.org/10.1155/2022/3573608
