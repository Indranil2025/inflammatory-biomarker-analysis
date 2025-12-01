Inflammatory marker gene analysis among neuropsychiatric disorders

This repository contains all code used for analysing inflammatory marker genes across different neuropsychiatric disorders. The workflow includes: Differential gene expression analysis; Diagnostic evaluation using ROC curves; Immune cell-type deconvolution

Each analysis module has its own folder with standalone scripts.

1. Differential expression analysis (edgeR)

Users should begin with the differential expression workflow using the edgeR package.
All required scripts are provided inside the EDGER folder.

Key steps included in the scripts:
Importing the count matrix
Matching sample names in the metadata
Creating factor groups
Preparing the DGEList
Adding gene annotation
Generating DE gene tables

2. ROC–AUC analysis (pROC)

Diagnostic potential of genes can be assessed using ROC curves generated through the pROC package.
Scripts for this analysis are provided inside the PROC folder.

The workflow includes:
Importing expression or normalized data
Running ROC analysis per gene
Calculating AUC values
Saving ROC outputs

3. Immune cell-type deconvolution (EPIC)

Immune infiltration estimates are generated using the EPIC package.
Scripts for this analysis are provided inside the EPIC folder.

The workflow includes:
Importing processed expression matrices
Running EPIC deconvolution
Exporting cell-type fraction matrices
