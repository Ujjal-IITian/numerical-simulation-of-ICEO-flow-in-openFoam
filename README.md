# Induced-Charge Electroosmotic Flow Around a Half-Conducting Cylinder

[![DOI](https://shields.io)](https://doi.org)
[![Journal](https://shields.io)](https://acs.org)

## Overview

Numerical study of **induced-charge electroosmotic (ICEO) flow around a half-conducting cylinder** using **OpenFOAM**.

This repository contains simulation setups, meshes, and post-processed results associated with our peer-reviewed research article:
* **Paper Title:** Asymmetric Induced-Charge Electroosmotic Flows around Partially Conducting Cylinders in Shear-Thinning Fluids
* **Authors:** Saurabh Maurya, Avinash Mourya, Ujjal Das, Nilanjan Dutta, Mohit Trivedi, and Neelkanth Nirmalkar*
* **Journal:** *Industrial & Engineering Chemistry Research* (2026)
* **Full Article Link:** [https://doi.org](https://doi.org)

## Tools

* **OpenFOAM** (`rheoTool`)
* **blockMesh**
* **ParaView**
* **Tecplot**

## Work Performed

* Developed computational domains and structured meshes using `blockMesh`.
* Configured and validated OpenFOAM simulations against published results.
* Analyzed ICEO flow behavior around a half-conducting cylinder in Newtonian and power-law shear-thinning fluids.
* Post-processed and visualized velocity fields, charge density, and streamlines using ParaView and Tecplot.

## Abstract

In this two-dimensional computational study, induced-charge electroosmosis (ICEO) around a half-conducting Janus cylinder immersed in a power-law shear-thinning electrolyte is considered within a fully coupled Poisson–Nernst–Planck–Stokes (PNP-Stokes) formulation, with the selected range of the flow-behavior index providing a systematic framework to investigate the influence of shear-dependent viscosity on ICEO-induced transport. The asymmetric surface conductivity of the Janus cylinder breaks the classical dipolar symmetry of ICEO, producing localized polarization zones, unequal counter-rotating vortices, and strongly modified azimuthal velocity distributions. Incorporation of a power-law rheological model demonstrates that shear-thinning behavior significantly amplifies the induced near-surface flow, enlarges recirculation regions, and enhances convective ion transport. The simulations show that the coupling between nonlinear double-layer polarization and shear-dependent viscosity leads to a nonlinear voltage-velocity response that deviates from the classical quadratic ICEO scaling and enhances local ionic mixing. The influence of applied potential ($\phi^* = 0.1\text{--}3$), Debye parameter ($\kappa = 6\text{--}10$), and flow-behavior index ($n = 0.6\text{--}1$) on the induced flow, charge distribution, current density, and mixing performance is systematically examined. These results demonstrate that both surface-conductivity asymmetry and fluid rheology influence nonlinear ICEO transport, providing insight into the design and control of electrokinetic flows in microfluidic systems involving non-Newtonian electrolytes.

## Citation

If you use this repository or reference our findings, please cite our published paper:

```bibtex
@article{maurya2026asymmetric,
  title={Asymmetric Induced-Charge Electroosmotic Flows around Partially Conducting Cylinders in Shear-Thinning Fluids},
  author={Maurya, Saurabh and Mourya, Avinash and Das, Ujjal and Dutta, Nilanjan and Trivedi, Mohit and Nirmalkar, Neelkanth},
  journal={Industrial \& Engineering Chemistry Research},
  year={2026},
  publisher={ACS Publications},
  doi={10.1021/acs.iecr.6c04036},
  url={https://doi.org}
}
```
