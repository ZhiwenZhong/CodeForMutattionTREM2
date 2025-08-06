# CodeForMutationTREM2
**Structural Impact of Alzheimer’s Disease Mutations on Transmembrane TREM2-DAP12 Interactions: An Atomistic Perspective**

This repository contains the scripts and workflows used in the study:  
**Zhong Z., Ulmschneider M.B., Lorenz C.D. (2025). Structural Impact of Alzheimer’s Disease Mutations on Transmembrane TREM2-DAP12 Interactions: An Atomistic Perspective. bioRxiv.**  
DOI: [10.1101/2025.06.26.661739](https://www.biorxiv.org/content/10.1101/2025.06.26.661739v1)

---

## Overview
This project investigates the effects of Alzheimer’s disease-associated mutations on the **transmembrane TREM2-DAP12 complex**, a critical signaling unit in microglial function, using **all-atom molecular dynamics (MD) simulations**.  
We analyzed:
- Structural perturbations introduced by pathogenic mutations in TREM2.
- Impact on stability and dynamics of the TREM2-DAP12 complex in membrane environments.
- Altered inter-residue contacts, hydrogen bonding, and lipid interactions caused by these mutations.

---

## Repository Contents
- **`scripts/`**  
  Python scripts for:
  - Trajectory analysis (RMSD, RMSF, interfacial contacts).
  - Hydrogen bonding and salt-bridge analysis.
  - Lipid interaction profiling.
  Jupyter notebooks demonstrating mutation effect visualization.
- **`data/`**  
  Example processed data and result summaries.

---

## Requirements
- **GROMACS** (version ≥ 2021)
- **Python 3.x** with:
  - `MDAnalysis`
  - `NumPy`
  - `Matplotlib`
  - `Pandas`
  - `Seaborn`

---
