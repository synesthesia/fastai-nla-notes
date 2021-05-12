# Workbooks for FastAI Numerical Linear Algebra

My working notes  for the Fast AI course [Numerical Linear Algebra](https://github.com/fastai/numerical-linear-algebra/blob/master/README.md)

## Getting  started

* Windows 10
* WSL2 installed and working
* Docker Desktop installed and working, using WSL2 as container backend
* open your preferred WSL2 distro
* clone this repo into a folder in that distro filesystem, cd into the working copy
* `code .`
* in VS Code make sure you have the  preferred extensions loaded
* in VS Code open command palette `CTRL-SHIFT-P`
* `Remote-Containers: Reopen In Container`
* wait for VS Code to reopen and for container to finish building
* open `0test-setup/test1.ipynb` and follow the [Microsoft tutorial for running Jupyter notebooks in VS Code](https://code.visualstudio.com/docs/python/data-science-tutorial)



 
## Colophon

This repo makes use of the VS Code Remote-Containers approach.

Based on the Microsoft example dev container [python-3-anaconda](https://github.com/microsoft/vscode-dev-containers/tree/master/containers/python-3-anaconda), with the addition of the [Keras](https://keras.io/about/) Python package and [XeLatex](https://nbconvert.readthedocs.io/en/latest/install.html#installing-tex) to support  PDF export of notebooks.
