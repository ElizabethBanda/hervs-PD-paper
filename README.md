# RNA-seq Analysis of Parkinson’s Disease Whole Blood

## Overview 

This repository contains scripts used for RNA-seq analysis of whole blood samples to characterize host gene and human endogenous retroviral (HERV) expression in Parkinson’s disease. 
Results are omitted prior to publication.


## Data availability 
Raw sequencing data, alignment files and counts data for each sample are available at the LONI IDA, (https://doi.org/10.25504/FAIRsharing.r4ph5f) and Parkinson’s Progression Markers Initiative Data Repository (https://www.michaeljfox.org/news/ppmi-rna-sequencing-project). Clinical data are available through Parkinson’s Progression Markers Initiative (https://www.ppmi-info.org/).

## Workflow
1.Retrotranscriptome quantification \
2. Differential expression: Gene and HERVs \
3. Cell Type Abundance \
4. Proximal Gene Set Enrichment

## Software Used 
Linux and R Studio

Seperate tools:
Cibersortx (https://cibersortx.stanford.edu/)

## Two scripts provided:
- HERV_HPC_workflow.sh: This is a SLURM job submission script for running Telescope on High-Performance Computing (HPC) clusters. It's designed to quantify transposable element expression from RNA-seq BAM files.
- HERV_analysis_Rworkflow.Rmd: This is a comprehensive R Markdown workflow for analyzing HERVs and differential gene expression in Parkinson's Disease using RNA-seq data from the PPMI (Parkinson's Progression Markers Initiative) cohort and supplementary data from the manuscript.

