# 🧬 RNA-Seq Analysis of Ferulic Acid–Treated Macrophages (GSE300705)

This repository contains a beginner-friendly RNA-Seq analysis pipeline focused on understanding how **Ferulic Acid** modulates inflammatory responses in **mouse macrophages**. The dataset used is publicly available via **GEO Series GSE300705**.

---

## Project Overview

- **Organism**: *Mus musculus* (mouse)
- **Experimental Design**: Control vs. Ferulic Acid–treated macrophages
- **Goal**: Identify differentially expressed genes and visualize the transcriptomic changes associated with anti-inflammatory treatment

---

## Technologies & Tools

- R / RStudio
- `DESeq2` for differential gene expression analysis
- `ggplot2`, `pheatmap` for visualization
- `GEOquery` to download GEO datasets

---

## 📁 Folder Structure
rna-seq-ferulic-acid-macrophages/
├── data/ # Processed or raw input files
├── results/ # DESeq2 outputs, plots
├── scripts/ # R scripts and .Rmd notebooks
└── README.md # Project documentation
