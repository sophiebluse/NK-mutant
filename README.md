# NK-mutant
# Mutation-specific dynamic remodeling of catalytic competence in nattokinase

This repository contains input structures, simulation protocols,
analysis scripts, processed data, and representative structures
associated with the manuscript:

"Activity-enhancing Mutations Encode Distinct Dynamic Regimes of Substrate Recognition and Catalytic Preorganization in Nattokinase"

## Systems

Eight simulation systems were investigated:

| Protein | Apo | AAPF-bound |
|---|---|---|
| WT | WT_apo | WT_sub |
| D36G | D36G_apo | D36G_sub |
| Q59E | Q59E_apo | Q59E_sub |
| G131A | G131A_apo | G131A_sub |

Three independent 1-μs replicas were generated for each condition.

Total production sampling: 24 μs.

## Software

- Amber24
- AmberTools / cpptraj
- Bio3D
- CHARMM-GUI
- Gaussian 16
- VMD
- R
- Python

## Main analyses

1. RMSD, Rg and RMSF
2. Binding-pocket and substrate RMSD
3. Catalytic geometry
4. PCA and free-energy landscapes
5. MM/GBSA
6. DCCM
7. Residue interaction networks
8. Suboptimal communication pathways
