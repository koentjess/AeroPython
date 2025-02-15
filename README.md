[![DOI](https://zenodo.org/badge/20401/leal26/AeroPy.svg)](https://zenodo.org/badge/latestdoi/20401/leal26/AeroPy)

# Fork
This is a fork of (https://github.com/leal26/AeroPy). It has has a namechange to be able to use it with pip, because (https://bitbucket.org/lukas-mueller/aeropy) also exists.

# Note
Because this is a fork, the documentation (http://aeropy.readthedocs.org/) uses the old 'aeropy' module. Replace 'aeropy' with 'aeropython' to get it working. This is also for the examples provided with this module.

# AeroPy
AeroPy is an library for calculating aerodynamic properties. The main feature of this library is the Python interface with XFOIL. The main objective of this library is to be able to use XFOIL via Python iteratively in a total of 4 lines total (one line for most uses). Through this interface coupling with other softwares (Abaqus, Ansys, etc) is possible and iterative processes (optimization, design sensitivity) are possible. For a thorough explanation please check the documentation and the tutorials. For thorough documentation and tutorials please check the [AeroPy website](http://aeropy.readthedocs.org/)

# Installation
- Open command line
- Run 'pip install aeropython'

# Installation from github
- Clone via GitHub
- Open command line in aeropython directory
- Run 'pip install .\'

# Dependencies
- subprocess
- os
- numpy
- math
- shutil
- datetime
- time
- scipy
- matplotlib
- pickle
- mpl_toolkits
- multiprocessing
- stl
- warnings
- paraview (if running inside Paraview)
