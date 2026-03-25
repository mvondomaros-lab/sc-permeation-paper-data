# sc-permeation-paper-data

Simulation inputs (structures, topologies, and parameters) to reproduce the molecular dynamics simulations reported in:

Rinto Thomas, Praveen Ranganath Prabhakar, Douglas J. Tobias, and Michael von Domaros,  
**Modeling Diffusion and Permeation Across the Stratum Corneum Lipid Barrier**, *ACS ES&T Air* **2026**, *3* (2), 580–589.  
https://pubs.acs.org/doi/10.1021/acsestair.5c00412

## Overview

This repository provides ready-to-run input decks for simulations of passive permeation across a model stratum corneum (SC) lipid membrane for three permeants:

- water
- acetone
- 6-methyl-5-hepten-2-one (6mho)

Each system directory is self-contained and includes the system coordinates, topology, parameters, and the NAMD configuration used in the study.

## Repository layout

```
.
├── 6mho/
│   ├── coordinates.pdb
│   ├── structure.psf
│   ├── parameters.prm
│   ├── box.xsc
│   ├── flags.pdb
│   ├── WTM_colvars.in
│   └── namd.conf
├── acetone/
│   ├── coordinates.pdb
│   ├── structure.psf
│   ├── parameters.prm
│   ├── box.xsc
│   ├── flags.pdb
│   ├── WTM_colvars.in
│   └── namd.conf
└── water/
    ├── coordinates.pdb
    ├── structure.psf
    ├── parameters.prm
    ├── box.xsc
    ├── flags.pdb
    ├── WTM_colvars.in
    └── us.conf
```

## Software requirements

- NAMD with Colvars support
- Optional visualization tools (e.g., VMD)

## Citation

If you use this repository, please cite:

Thomas, R.; Prabhakar, P. R.; Tobias, D. J.; von Domaros, M.  
*Modeling Diffusion and Permeation Across the Stratum Corneum Lipid Barrier.*  
arXiv:2510.14606 (2025).
