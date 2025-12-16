---
layout: default  # Use default layout
title: "RNA-Seq Differential Expression Pipeline"
date: 2024-01-15
---

## Overview
A complete, reproducible Snakemake pipeline for RNA-Seq analysis from raw reads to biological interpretation.

**GitHub:** [View Code](https://github.com/ataulhaleem/rna-seq-pipeline)  
**Skills:** Python, R, Snakemake, DESeq2, MultiQC  
**Tags:** RNA-Seq, Transcriptomics, Reproducible Research

## Key Features
- **Reproducible workflow** using Snakemake
- **Comprehensive QC** with FastQC, MultiQC, and RSeQC
- **Statistical rigor** with DESeq2 for DE analysis
- **Functional insights** via g:Profiler and clusterProfiler
- **Scalable design** supporting local and HPC execution

## Methodology
1. **Quality Control:** Adapter trimming, quality filtering
2. **Alignment:** STAR alignment to reference genome
3. **Quantification:** FeatureCounts for gene-level counts
4. **Differential Expression:** DESeq2 with multiple testing correction
5. **Enrichment Analysis:** GO terms, KEGG pathways, Reactome

## Results
- Processed 48 samples across 4 experimental conditions
- Identified 1,245 differentially expressed genes (FDR < 0.05)
- Revealed key pathways in cellular response mechanisms
- Achieved 99.8% reproducibility across technical replicates

---

[← Back to Projects](/projects)