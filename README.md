# NLMOO23
Codes for the Nonlinear Multiobjective Optimization course 2023

# Installation instructions
* Install Python 3.10 and Poetry
* Clone this repository
* Create and activate a virtual environment (Python 3.10) in the downloaded folder using [this guide](https://janakiev.com/blog/jupyter-virtual-envs/)
* Run `poetry install`

Troubleshooting:

- When using a virtual environment, you might need to create a custom kernel for jupyterlab to use. To do so, you can use the following command: `python -m ipykernel install --user --name nameofkernel`. You can replace `nameofkernel` with whatever you want to name your custom kernel. This name will be displayed when selecting a kernel in jupyterlab.

- If everything else fails, you can run the notebooks in binder by clicking the _Binder_ badge at the top of this README or by following [this link](https://mybinder.org/v2/gh/industrial-optimization-group/NLMOO23/HEAD). Note that using binder is significantly slower than running the notebooks locally.

