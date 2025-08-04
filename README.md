# 🪱 Cellular Drivers of Divergent Reproductive Fates in *P. morgani*

This repository contains the analysis notebook, results, and presentation slides from a study on the cellular mechanisms underlying reproductive fate decisions in the freshwater planarian *Phagocata morgani*.

## 🪱 Overview

Developmental bifurcations represent critical transitions where organisms diverge into distinct phenotypic fates. In *P. morgani*, individuals develop into either a **sexual** or **asexual** reproductive phenotype—each associated with a distinct growth trajectory. The specific cellular populations that guide this bifurcation remain poorly characterized.

This repository presents a **quantitative framework** to:

- Infer trajectories using pseudotime
- Identify bifurcation points along these trajectories
- Model cell-type abundance and variance changes across transitions
- Statistically detect cell types enriched near bifurcation points that may drive reproductive fate
- Model size-independent covariance in the cell types

## 📂 Repository Structure
```
Main Files
├── Dorrity_Lab_EMBL.Rmd # Main analysis notebook
├── size-cds-cellcounts_3e-5-highRes-cell-type.rds # Input data
├── Work_Presentation.pptx # Summary presentation of the study

Output Directories
├── trajectory_output/ 
├── abundance_output/
├── variance_output/
├── combined_analysis_output/
├── covariance_output/


Extras
├── bifurcation.jpeg # Illustration for README
├── worm.jpeg # Illustration used in index.html
├── index.html # Rendered notebook output
└── README.md # Project overview and instructions
```

## 📎 Requirements

All analyses are performed within an RNotebook framework using R (version 4.4.2). The Monocle3 package [(Trapnell lab)](https://github.com/cole-trapnell-lab/monocle3) is utilized for single-cell trajectory inference and normalization. Dependencies including Bioconductor packages and common data manipulation and visualization libraries are mentioned in the RNotebook "Dorrity_Lab_Embl.Rmd".

## 🪱 How to Run the Analysis

To reproduce the full analysis:

1. **Clone this repository:**
   ```bash
   git clone https://github.com/Aishwarya-Girish/Dorrity-Lab-EMBL.git
   cd Dorrity-Lab-EMBL
2. Open `planarian_reproductive_fate_drivers.Rmd` in RStudio.
3. Run the notebook or run chunks interactively to reproduce results.

## 🪱 Academia Bifurcations: This is not a UMAP, it's a career path 😁

![alt text](https://github.com/Aishwarya-Girish/Dorrity-Lab-EMBL/blob/main/bifurcation.jpeg)
