# Neutron Star Structure

A numerical investigation of how gravity, pressure, and the equation of state determine the structure of neutron stars.

## Goals

* Model stellar structure using Newtonian hydrostatic equilibrium.
* Explore how central density affects mass and radius.
* Investigate different equations of state, beginning with a polytropic EOS.
* Extend the model to general relativity using the Tolman-Oppenheimer-Volkoff (TOV) equations.
* Investigate neutron-star mass-radius relationships and maximum stable mass.

## Physics

The initial model solves

$$
\frac{dP}{dr} = -\frac{Gm(r)\rho(r)}{r^2}
$$

with a polytropic equation of state,

$$
P = K\rho^\gamma
$$

The project will progressively replace these simplified assumptions with more realistic physics.

## Current Progress

**01 | Newtonian Stellar Structure**

* Numerical hydrostatic equilibrium model analysis

## Tools

Python • NumPy • SciPy • Matplotlib • Jupyter

## Future Work

* Realistic neutron-star EOS
* Mass-radius curves
* Maximum neutron-star mass
* Newtonian vs. relativistic comparison
* TOV equations
