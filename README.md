# Hydrophobic Surface Analysis
A Google Colab notebook (hydrophobic_surface_analysis.ipynb) for analyzing protein solvent-accessible surface area (SASA) from PDB files, with a focus on the exposed hydrophobic surface. It computes total SASA, hydrophobic SASA, hydrophobic fraction, and an estimated isoelectric point (pI), and provides both per-residue plots and an interactive 3D view.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mar4mn/Hydrophobic-Surface-Analysis/blob/main/hydrophobic_surface_analysis.ipynb)

## Outputs

The notebook can export a ZIP (`sasa_results.zip`) containing:

`*_per_residue_sasa.csv` (per structure): per-residue SASA table including residue identity and hydrophobic flag

`*_summary.csv` (per structure): total SASA, hydrophobic SASA, hydrophobic fraction, predicted pI

`comparative_summary.csv`: combined overview across all uploaded structures
