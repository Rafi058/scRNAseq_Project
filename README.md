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
# scRNAseq_Project: PBMC 3k Single-Cell Analysis

This project performs a step-by-step analysis of the 10x Genomics PBMC 3k dataset using Scanpy. The pipeline includes preprocessing, clustering, dimensionality reduction, marker gene detection, and visualization.

---

## 🧪 Technologies Used

- Python 3.10+
- Jupyter Notebook
- [Scanpy](https://scanpy.readthedocs.io/en/stable/)
- [AnnData](https://anndata.readthedocs.io/en/latest/)
- matplotlib & seaborn
- pandas & numpy

---

## 🧬 Analysis Workflow

### 🔹 Step 1: Load Dataset
- Load with `scanpy.datasets.pbmc3k()` or from a local `.h5ad` file

### 🔹 Step 2: Preprocessing
- Filter low-quality cells and genes
- Normalize and log-transform the data
- Identify highly variable genes
- Scale data and run PCA

### 🔹 Step 3: Dimensionality Reduction & Clustering
- Construct a neighborhood graph
- Perform Leiden clustering
- Visualize clusters using UMAP

### 🔹 Step 4: Cell Type Annotation
- Annotate clusters based on known immune cell types
- Visualize cell types on the UMAP

### 🔹 Step 5: Marker Gene Detection
- Rank marker genes for each cluster
- Visualize with heatmaps, violin plots, and dotplots

### 🔹 Step 6: Save Outputs
- Export processed data (`.h5ad`)
- Save plots and marker gene tables to `results/` and `figures/`

---

## 🧾 Sample Output

![UMAP Cell Types](figures/umap_cell_types.png)  
*UMAP plot of PBMC clusters annotated by cell type*

---

## 🔁 How to Reproduce

Clone the repository:

```bash
git clone https://github.com/rafi058/scRNAseq_Project.git
cd scRNAseq_Project

