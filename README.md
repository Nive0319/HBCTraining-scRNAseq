# HBCTraining-scRNAseq

## Overview
Single-cell RNA-seq analysis of PBMCs (control vs stimulated) using Seurat v5.

## Steps performed
- Quality control & filtering
- Normalization & scaling
- PCA & UMAP
- Integration (CCA/Harmony)
- Clustering & marker identification

## Key files
- `scripts/` - All analysis R scripts from the workshop
- `top_markers.csv` - Top 5 marker genes per cluster
- `marker_genes.png` - UMAP feature plots for selected markers

## Results summary
![Marker genes](marker_genes.png)
