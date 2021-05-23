# differential_equations_models

This is a showcase of differential equations models and solvers coded in python.

## Disclaimer

Some packages used presented to be unable to run in Windows enviroments using a standard Python enviroment.
Therefore, we suggest using a Conda environment to execute any run.

## Using Pyomo solvers

Pyomo is a Python-based, open-source optimization modeling language with a diverse set of optimization capabilities.
Their documentation can be accessed [here](https://pyomo.readthedocs.io/en/stable).
One comment to add up is that installation of Pyomo was not trivial task on Windows pip enviroment. 
An installation using an Anaconda Distribution is highly recommended.

### General approach to solving Optimal Control Problems in Pyomo
* Initialize boundary values
* Initialize concrete Model
* Define independent variables
* Define dependent variables
* Define ODE Derivatives
* Define ODE Constraints
* Define Boundary values constraints list
* Define objective function
* Run mesh discretizer
* Run with selected solver

### Used libraries
* pyomo.environ:
    * Pyomo library used to define the optimization models.
* pyomo.dae
    * Modeling extension library that allows the incorporation of differential algebraic equations (DAE) on pyomo.
* numpy
   * Mathematical computing library.
* matplotlib.pyplot
    * Mathematical plotting library.
* plotly
    * Plotting library used for animations.
  
### Projects
* Brachistochrone
* Rocket car



