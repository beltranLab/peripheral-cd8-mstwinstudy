# Twin study identifies early immunological and metabolic dysregulation of CD8+ T cells in multiple sclerosis

## About
Multiple sclerosis (MS) is an inflammatory neurological disease of the central nervous system with a subclinical phase preceding frank neuroinflammation. CD8+ T cells are abundant within MS lesions, but their potential role in disease pathology remains unclear. Using high-throughput single-cell RNA sequencing and single-cell T cell receptor analysis, we compared antigen-experienced CD8+ T cell clones from the blood and cerebrospinal fluid (CSF) of monozygotic twin pairs in which the co-twin had either no, or subclinical neuroinflammation (SCNI). We identified peripheral MS-associated immunological and metabolic alterations indicative of an enhanced migratory, proinflammatory, and activated CD8+ T cell phenotype, which was also evident in co-twins with SCNI and in an independent validation cohort of people with MS (pwMS). Together, our in-depth single-cell analysis indicates a disease-driving proinflammatory role of infiltrating CD8+ T cells and identifies potential immunological and metabolic therapeutic targets in both prodromal and definitive stages of the disease.

Here we selected 12 twin pairs from the MS TWIN STUDY cohort, representing a sub-cohort comprising 12 MS-affected individuals, and their non-neuroinflammatory (n=6) or SCNI-affected (n=6) co-twins. We then applied **high-throughput scRNA-seq and single-cell T-cell receptor (TCR) sequencing** to characterize peripheral and CNS-migrated CD8+ T cells in each group, revealing distinct MS-associated immunological and metabolic alterations. These data pave the way for further understanding of pathological mechanisms underpinning disease onset and manifestation, and open new prospects for targeted diagnostic and therapeutic approaches in MS.

## Description and analysis workflow
### For the twins cohort:
If you plan to use the **10X output** as the starting point for the analysis, please proceed to the notebook **"Preparation_Markers_CD8"** (containing the integration, clustering, identification of matching clonotypes between CSF and PBMCs and general plotting of UMAPs and subpopulation markers). If you plan to use the **.rds Seurat object**, you can perform the T cell clonotypes matching between CSF and PBMCs, and then directly proceed to the notebook **"DGE_analysis"** (containing further steps for disease-specific comparisons and materials for Fig. 2-4). 
### For the validation cohort:
If you plan to use the **10X output** as the starting point for the analysis, please proceed to the notebook **"Mapping_sypmohony_PBMC"** containing all necessary scripts for mapping, cluster prediction, analysis and Fig. 5 plots generation. If you use the **.rds Seurat object**, you may start from the chunk **"6. Create expression matrix for each diagnosis with selection of features and filtering"** and follow the steps for further analysis.

The required packages(with versions) are listed in the output of the first chunk of each notebook. 
