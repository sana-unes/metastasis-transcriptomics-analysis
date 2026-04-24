# Transcriptomic Analysis of Organ-Specific Metastatic Adaptation in Breast Cancer

## Research Question
Can transcriptomic data reveal organ-specific adaptation programs in metastatic breast cancer, particularly in liver-tropic cells?

---

## Background
Metastasis is the leading cause of cancer-related mortality and is known to exhibit organ-specific patterns. Successful colonization of distant organs depends not only on tumor-intrinsic factors but also on the ability of cancer cells to adapt to the target microenvironment. This project explores whether transcriptomic differences between organ-tropic metastatic sublines reflect such adaptive processes.

---

## Dataset
- **GSE62598 (GEO)**
- Mouse 4T1 breast cancer model
- Groups:
  - Parental
  - Primary tumor
  - Lung-aggressive
  - Bone-aggressive
  - Liver-aggressive
- Sample size: **n = 3 per group**

---

## Methods
- Probe-to-gene mapping using platform annotation (GPL)
- Construction of gene-level expression matrix
- Selection of top 1000 most variable genes
- Principal Component Analysis (PCA)
- Differential expression analysis (Welch’s t-test)
- Pathway enrichment analysis (Enrichr, KEGG)

---

## Key Results
- PCA revealed **partial separation of liver-tropic cells** along a dominant axis of variation
- Liver and lung sublines showed **modest transcriptional differences**
- Liver vs bone comparison showed **greater divergence and heterogeneity**
- No genes passed strict multiple-testing thresholds due to limited sample size
- Exploratory analysis identified:
  - 373 genes (liver vs lung)
  - 708 genes (liver vs bone)
- Pathway enrichment consistently highlighted **metabolic pathways**

---

## Interpretation
These results suggest that organ-specific metastasis is not driven by large, uniform gene expression changes, but rather by subtle, coordinated transcriptional programs. The recurring involvement of metabolic pathways—particularly lipid, amino acid, and central carbon metabolism—supports a model in which metastatic fitness depends on adaptation to the metabolic constraints of the target microenvironment.

---

## Limitations
- Small sample size (n = 3 per group)
- Limited statistical power
- Microarray platform constraints
- Enrichment results not statistically significant after correction

---

## Future Directions
- Apply analysis to RNA-seq datasets with larger sample sizes
- Integrate single-cell or spatial transcriptomics data
- Perform metabolic pathway scoring across metastatic datasets
- Investigate microenvironment-dependent signaling interactions

---

## Author
Sana Younes  
