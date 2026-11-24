# EgyE332 | Energy Optimization and System Dynamics

This repository contains worked Jupyter notebooks for the optimization part of a graduate-level Energy Engineering course, EgyE332, taught at the University of the Philippines, Diliman. The examples cover optimization modeling in Pyomo, linear and mixed-integer linear programming, nonlinear optimization, and surrogate-based optimization. Applications include power system operations, fuel management, renewable energy, energy investment, and heat exchanger design.

## Table of contents

* Introduction
  * [Introductory Pyomo examples](https://github.com/kspilario/EgyE332_opti/blob/main/Introduction/intro_pyomo_examples.ipynb) 
* Linear programming (LP)
  * [Simple economic dispatch](https://github.com/kspilario/EgyE332_opti/blob/main/LP%20Problems/simple_econ_dispatch.ipynb)
  * [Economic dispatch with renewables and storage](https://github.com/kspilario/EgyE332_opti/blob/main/LP%20Problems/econ_dispatch_RE_storage.ipynb)
  * [Fuel procurement, inventory, and power dispatch](https://github.com/kspilario/EgyE332_opti/blob/main/LP%20Problems/fuel_scheduling_with_inventory.ipynb)
  * [Fuel blending with the simplex method](https://github.com/kspilario/EgyE332_opti/blob/main/LP%20Problems/simple_fuel_blending.ipynb)
* Mixed-integer linear programming (MILP)
  * [Simple unit commitment](https://github.com/kspilario/EgyE332_opti/blob/main/MILP%20Problems/simple_unit_commitment.ipynb)
  * [Unit commitment with solar, wind, and battery storage](https://github.com/kspilario/EgyE332_opti/blob/main/MILP%20Problems/unit_commitment_RE_storage.ipynb)
  * [Energy investment selection as a 0–1 knapsack problem](https://github.com/kspilario/EgyE332_opti/blob/main/MILP%20Problems/energy_investment_knapsack.ipynb)
  * [Waste-to-energy facility location and allocation](https://github.com/kspilario/EgyE332_opti/blob/main/MILP%20Problems/wte_facility_location_allocation.ipynb)
* Nonlinear optimization (NLP)
  * [Nonlinear economic dispatch with three formulations](https://github.com/kspilario/EgyE332_opti/blob/main/NLP%20Problems/econ_dispatch_nonlinear.ipynb)
  * [Economic dispatch with valve-point effects using particle swarm optimization](https://github.com/kspilario/EgyE332_opti/blob/main/NLP%20Problems/econ_dispatch_2D_valve_point.ipynb)
  * [Cascaded dam scheduling](https://github.com/kspilario/EgyE332_opti/blob/main/NLP%20Problems/cascaded_dams_scheduling.ipynb)
  * [Solar PV maximum power point](https://github.com/kspilario/EgyE332_opti/blob/main/NLP%20Problems/solar_max_power.ipynb)
  * [Wind farm layout optimization](https://github.com/kspilario/EgyE332_opti/blob/main/NLP%20Problems/wind_farm_layout.ipynb)
* Surrogate optimization
  * [Heat exchanger optimization with a surrogate model](https://github.com/kspilario/EgyE332_opti/blob/main/Surrogate%20Optimization/heat_exchanger_surrogate_opti.ipynb)
  * [Bayesian optimization of a heat exchanger](https://github.com/kspilario/EgyE332_opti/blob/main/Surrogate%20Optimization/heat_exchanger_bayesopt.ipynb)

## Installing Pyomo, GLPK, and IPOPT

[Pyomo](https://www.pyomo.org/) is the Python package used to formulate optimization models. [GLPK](https://www.gnu.org/software/glpk/) solves linear programming (LP) and mixed-integer linear programming (MILP) problems. [IPOPT](https://coin-or.github.io/Ipopt/) solves continuous nonlinear programming (NLP) problems.

To install these, run the following on the terminal:

```bash
conda install -c conda-forge pyomo
conda install -c conda-forge glpk
conda install -c conda-forge ipopt
```

## Contributing
If you find any issues, you can send me an email at <kspilario@up.edu.ph>

## Instructor
Karl Ezra S. Pilario, Ph.D. | See my [Website](https://kspilario.github.io)
