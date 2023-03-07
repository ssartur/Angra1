# Angra 1 Full Core Model

This repository contains a notebook for generating OpenMC input files of a detailed Angra 1 full core model model as well as a notebook for analyzing the simulation results.

Angra 1 is a nuclear power plant located at Angra dos Reis, Rio de Janeiro, Brazil. It is a pressurized water reactor composed of 121 fuel assemblies. Each fuel assembly is an array of 16x16 fuel rods, burnable poison rods or guide tubes.

<img src = 'Angra 1 Full Core Plot.png'>

## Dependencies

In addition to [OpenMC](https://github.com/openmc-dev/openmc), this repository relies on [NuReMa](https://github.com/ssartur/NuReMa) for performing thermal expansion and calculating materials densities as functions of temperature and/or pressure.