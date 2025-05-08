# BINF_Group_Project

This repository includes scripts and outlines of data analysis for my final project in Bioinformatics at Augustana University.

My portion of the project is looking at the expression of APOE gene variants by tissue types in the body. 

# Data
My data was obtained from https://www.gtexportal.org/home/gene/APOE under the heading "Significant Single-Tissue eQTLs for APOE (ENSG00000130203.10) in all tissues"

This data is significant expression data including the variant ID, the SNP ID, the Phenotype ID(s), the Intron ID, the P-Value, NES values, and Tissue Sample. 

# Scripts
Scripts included in this repository are draft scripts for analyzing this data in R using R Studio.

The current script includes data analysis of Box Plot and PCA analysis; however, after further inspection of the data set, a heatmap is the best representation of variant tissue expression.

The .rmd file labeled "BINF_Final_Project" includes all R code that was run during the process of this project, including code that did not work nor was used in the final project.

The .rmd file labeled "APOE_Variant_Expression_Heatmaps" is a clean version of the R code that was used specifically with creating the heatmap analysis of APOE Variant Tissue Expression. The resulting heatmap was also included as a .png file to this repository. 
