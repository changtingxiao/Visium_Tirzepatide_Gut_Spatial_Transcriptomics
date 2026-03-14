# Visium Spatial Transcriptomics Analysis – Tirzepatide Gut Study

## Project description

This repository contains the analysis code, processed results, and figure generation workflows for the spatial transcriptomics analysis of rat gut tissue under different dietary and treatment conditions.

Study conditions:

- CD/PBS
- HFD/PBS
- HFD/TZP

The goal of this analysis was to investigate transcriptional changes associated with tirzepatide treatment using 10x Genomics Visium spatial transcriptomics data.

---

## Repository structure

code/
Analysis pipelines and RMarkdown workflows used to generate results and figures.

results/
Processed DEG tables and GO enrichment outputs used for manuscript figures.

plots/
Publication-quality figures and supplementary visualizations.

docs/
Analysis reports and documentation supporting the manuscript.

---

## Analysis components

Main analyses include:

- Spatial clustering and cell type annotation
- Differential expression analysis (HFD/TZP vs HFD/PBS)
- GO biological process enrichment
- UMAP visualization
- Volcano plots
- Heatmaps
- Pseudobulk expression summaries

---

## Data availability

Raw spatial transcriptomics sequencing data will be deposited in NCBI GEO.

Processed data supporting the findings are included in this repository.

---

## Software

Main tools used:

- R
- Seurat
- clusterProfiler
- enrichplot
- ggplot2
- dplyr

---

## Author

Tao Sun  
Bioinformatics analysis and visualization

---

## Correspondence

For questions regarding the study:

Dr. Changting Xiao  
University of Saskatchewan

