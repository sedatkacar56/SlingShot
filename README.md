# 📊 Slingshot Trajectory Inference and Visualization

This repository contains a complete R Markdown workflow for performing pseudotime trajectory inference using **Slingshot** and visualizing it with 2D/3D UMAP projections, pseudotime heatmaps, and gene expression trends.

---

## 📌 Overview

This project demonstrates how to:

- Convert a Seurat object to a 
- Run trajectory inference with the  package
- Visualize lineage paths using MST and smooth curves
- Project lineages onto UMAP (2D and 3D)
- Color by cluster and pseudotime using 
- Detect genes changing along trajectories using 
- Plot gene expression trends and heatmaps along pseudotime

---

## 📁 File Structure

- : Main R Markdown file with all steps and visualizations
- : Knitted HTML output with embedded plots
-  (optional): Folder for saved figures (if not using )

---

## 🧬 Input

A preprocessed **Seurat object** with:

- PCA and UMAP dimensionality reductions
- Cluster labels (e.g., ) stored in metadata

---

## 🚀 How to Use

1. Clone this repository or download the  and  files.
2. Open  in RStudio.
3. Ensure your Seurat object (e.g., ) is available in your environment.
4. Knit the file to generate the HTML report with embedded trajectory analysis.

---

## 📊 Outputs

- 2D UMAP plots with Slingshot MST and inferred trajectories
- Interactive 3D UMAP colored by cluster or pseudotime
- Pseudotime-ordered heatmaps of dynamic genes
- Smooth gene expression trends across pseudotime for selected markers

---

## �� Author

**Sedat Kacar**  
Postdoctoral Researcher  
Indiana University School of Medicine  
Division of Pulmonary, Critical Care, and Sleep Medicine

---

## 📜 License

Released under the MIT License. You may reuse, adapt, and redistribute with appropriate credit.

