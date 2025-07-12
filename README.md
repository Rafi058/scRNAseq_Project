<<<<<<< HEAD
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
=======
# scRNA_analysis
>>>>>>> 356ced321e68d72df50eae1e9827bba468fd2ce3
# scRNAseq_Project

This project analyzes the PBMC 3k single-cell RNA-seq dataset using Scanpy.

## Technologies Used
- Python 3.10
- Jupyter Notebook
- Scanpy
- AnnData
- pandas, numpy, matplotlib, seaborn

## Analysis Steps
1. Load dataset
2. Preprocessing
3. Clustering and UMAP
4. Cell type annotation
5. Marker gene detection
6. Save results

