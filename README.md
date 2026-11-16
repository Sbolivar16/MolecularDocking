<div align="center">

# 🧬 MolecularDocking

**Curated Google Colab & Python Workflows for Molecular Docking, Post-Docking Rescoring & Pharmacophore Analysis**

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sbolivar16/MolecularDocking/blob/main/GNINA_and_Vina_Analysis.ipynb)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![ORCID](https://img.shields.io/badge/ORCID-0000--0002--3772--7604-A6CE39?logo=orcid&logoColor=white)](https://orcid.org/0000-0002-3772-7604)
[![Portfolio](https://img.shields.io/badge/Portfolio-sbolivar16.github.io-0ea5e9)](https://sbolivar16.github.io)

</div>

---

## Overview

This repository provides ready-to-run **Google Colab** notebooks and analysis workflows designed for **molecular docking**, **virtual screening**, **MM/GBSA post-docking rescoring**, and **structure–activity visualization** in computational chemistry and *in silico* drug discovery.

---

## 1-Click Notebook Launchpad

| Category | Notebook | Description | Launch |
| :--- | :--- | :--- | :---: |
| **Docking Engines** | `PandaDock_V3_0_0.ipynb` | Updated PandaDock v3.0.0 protein–ligand docking workflow | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sbolivar16/MolecularDocking/blob/main/PandaDock_V3_0_0.ipynb) |
| **Docking Engines** | `PandaDock.ipynb` | PandaDock docking workflow in Google Colab | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sbolivar16/MolecularDocking/blob/main/PandaDock.ipynb) |
| **Docking Engines** | `gninasminadocking.ipynb` | GPU-accelerated GNINA & SMINA docking execution | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sbolivar16/MolecularDocking/blob/main/gninasminadocking.ipynb) |
| **SMILES to Docking** | `smile2dock.ipynb` | End-to-end ligand preparation from SMILES strings to docking | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sbolivar16/MolecularDocking/blob/main/smile2dock.ipynb) |
| **Post-Docking Analysis** | `GNINA_and_Vina_Analysis.ipynb` | Comparative scoring, CNN score/affinity & Vina pose analysis | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sbolivar16/MolecularDocking/blob/main/GNINA_and_Vina_Analysis.ipynb) |
| **Free Energy Rescoring** | `UniGBSA_PostDocking_Colab_EN.ipynb` | Automated MM/GBSA rescoring of docking poses using Uni-GBSA | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sbolivar16/MolecularDocking/blob/main/UniGBSA_PostDocking_Colab_EN.ipynb) |
| **Pharmacophore** | `5_PharmacophoreToolkit_PostDocking_Colab_EN.ipynb` | Post-docking pharmacophore mapping and interaction profiling | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sbolivar16/MolecularDocking/blob/main/5_PharmacophoreToolkit_PostDocking_Colab_EN.ipynb) |
| **Visualization** | `Heatmap_with_dendrogram.ipynb` | Hierarchical clustering heatmaps with dendrograms for docking scores | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sbolivar16/MolecularDocking/blob/main/Heatmap_with_dendrogram.ipynb) |
| **Statistical Analysis** | `Introduction_to_Docking_Data_Analysis_with_Linear_Regression.ipynb` | Linear regression modeling between docking scores and bioactivity | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sbolivar16/MolecularDocking/blob/main/Introduction_to_Docking_Data_Analysis_with_Linear_Regression.ipynb) |

---

## Suggested Multi-Stage Workflow

```text
SMILES Library (smile2dock.ipynb)
        │
        ▼
Docking Execution (gninasminadocking.ipynb / PandaDock_V3_0_0.ipynb)
        │
        ▼
Pose & Score Analytics (GNINA_and_Vina_Analysis.ipynb / Heatmap_with_dendrogram.ipynb)
        │
        ▼
Post-Docking Refinement (UniGBSA_PostDocking_Colab_EN.ipynb / PharmacophoreToolkit)
        │
        ▼
MD Preparation → https://github.com/Sbolivar16/MD-Prep-Studio
```

---

## Author & Citation

**Santiago Bolívar Ávila, Ph.D.**  
*Ph.D. in Chemical Sciences (UNR) · M.Sc. in Pharmaceutical Sciences*  
[ORCID](https://orcid.org/0000-0002-3772-7604) · [ResearchGate](https://www.researchgate.net/profile/Santiago-Bolivar-Avila) · [Portfolio](https://sbolivar16.github.io) · `sbolivaravila16@gmail.com`
