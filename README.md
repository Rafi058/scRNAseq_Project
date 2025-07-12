# PBMC 3k Single-Cell RNA-Seq Analysis

This project performs an end-to-end single-cell RNA sequencing analysis of the **PBMC 3k dataset** using Python and the `scanpy` library.

---

## Project Structure

```
scRNAseq_Project/
├── data/
│   └── raw/                         # Raw input files (e.g., pbmc3k.h5ad)
├── notebooks/
│   └── pbmc3k_analysis.ipynb       # Main notebook with all analysis steps
├── results/
│   ├── pbmc3k_processed.h5ad       # Saved AnnData object
│   └── marker_genes_by_cluster.csv
├── figures/
│   └── Plots saved by Scanpy (e.g., UMAP, violin, dotplot)
├── scripts/
│   └── download_pbmc3k.py          # Script to download the dataset
└── README.md                       # Project description
```
