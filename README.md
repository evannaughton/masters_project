# masters_project

## Project Description

This repository contains the code and data analysis scripts for my
Master's project titled "characterising the radiogenomic properties of
high Ki-67 index adrenocortical carcinoma". The study involves genomic,
radiomic, and statistical analyses to uncover significant biomarkers and
pathways associated with aggressive adrenocortical carcinoma.

## Repository Contents

1.  [cbioportal_transcriptomics.Rmd](#cbioportal_transcriptomics.Rmd)
    -   This Rmarkdown file contains code used to perform quartiling and
        segmentation of the TCGA-ACC samples based on MKI67 gene
        expression, survival analyses, tumour microenvironment analyses
        (xCell, CIBERSORTx, MCP-Counter), and additional exploratory
        analyses.
2.  [differential_expression_TCGA_ACC.Rmd](#differential_expression_TCGA_ACC.Rmd)
    -   This Rmarkdown file contains code used to perform differential
        gene, miRNA, and protein expression analyses on the extreme
        MKI67 expression cohorts as well as gene set enrichment analysis
        (GSEA).
3.  [copy_number_analysis_TCGA_ACC.Rmd](#copy_number_analysis_TCGA_ACC.Rmd)
    -   This Rmarkdown file contains code used to calculate total copy
        number alteration (CNA) scores from the amplification and
        deletion scores for each patient in the extreme MKI67 expression
        analysis, as well as additional analyses relating to total CNA
        scores.
4.  [transcriptomic_analysis_cna_quartiles.Rmd](#transcriptomic_analysis_cna_quartiles.Rmd)
    -   This Rmarkdown file contains code used to perform the
        supplementary analysis of extreme CNA score quartiles. The first
        portion contains a survival analysis in an attempt to replicate
        a previous survival analysis of extreme CNA quartiles (Langan et
        al., (2023)). The second portion contains an exploratory
        differential gene expression analysis on these selected
        quartiles, as well as a GSEA and some additional differential
        expression analyses.
5.  [Radiomics.Rmd](#Radiomics.Rmd)
    -   This Rmarkdown file contains code used to perform quantiling and
        segmentation of the TCIA Adrenal-ACC-Ki67-Seg samples based on
        their Ki-67 index value.
6.  [Radiomics.ipynb](#Radiomics.ipynb)
    -   This Jupyter Notebook file contains the code (Python) used to
        perform all radiomic analyses on our selected "high" and "low"
        Ki-67 index cohorts. Radiomic feature extraction was carried out
        using PyRadiomics.
7.  [Radiomics2.ipynb](#Radiomics2.ipynb)
    -   This Jupyter Notebook file contains the code (Python) used to
        perform an additional radiomic analyses using the same cohorts
        as the study carried out by the original authors of this
        dataset, Ahmed et al. The aim of this additional analysis was to
        replicate the original analysis as accurately as possible and to
        experiment with and obtain a Params.yaml file that was suited to
        our own radiomic analysis of extreme Ki-67 index cohorts.
8.  [Params.yaml](#Params.yaml)
    -   This .yaml file contains the parameters used to carry out batch
        radiomics analysis on our selected cohorts.

## Contact information

1.  [Evan Naughton](#Evan%20Naughton)
    -   MSc Biomedical Genomics, University of Galway, Ireland.
    -   Email(s):
        [E.NAUGHTON10\@universityofgalway.ie](mailto:E.NAUGHTON10@universityofgalway.ie){.email}
        \|
        [naughtonevan\@gmail.com](mailto:naughtonevan@gmail.com){.email}

## Acknowledgements

I would like to extend a sincere thank you to my supervisors Dr. Aaron
Golden and Dr. Conall Dennedy for their advice, feedback, and guidance
throughout the course of this project. I would also like to extend my
thanks to PhD candidate Parisa Taheri and HRB Summer Student Scholarship
recipient Eva Langan for their help and support during this project
also.
