---
title: "Exploring and analysing single cell multi-omics data with VDJView"
date: 2020-02-18
publishDate: 2020-07-15T02:45:06.284406Z
authors: ["Jerome Samir", "Simone Rizzetto", "Money Gupta", "Fabio Luciani"]
publication_types: ["2"]
abstract: "
**Background**
Single cell RNA sequencing provides unprecedented opportunity to simultaneously explore the transcriptomic and immune receptor diversity of T and B cells. However, there are limited tools available that simultaneously analyse large multi-omics datasets integrated with metadata such as patient and clinical information.
**Results**
We developed VDJView, which permits the simultaneous or independent analysis and visualisation of gene expression, immune receptors, and clinical metadata of both T and B cells. This tool is implemented as an easy-to-use R shiny web-application, which integrates numerous gene expression and TCR analysis tools, and accepts data from plate-based sorted or high-throughput single cell platforms. We utilised VDJView to analyse several 10X scRNA-seq datasets, including a recent dataset of 150,000 CD8+ T cells with available gene expression, TCR sequences, quantification of 15 surface proteins, and 44 antigen specificities (across viruses, cancer, and self-antigens). We performed quality control, filtering of tetramer non-specific cells, clustering, random sampling and hypothesis testing to discover antigen specific gene signatures which were associated with immune cell differentiation states and clonal expansion across the pathogen specific T cells. We also analysed 563 single cells (plate-based sorted) obtained from 11 subjects, revealing clonally expanded T and B cells across primary cancer tissues and metastatic lymph-node. These immune cells clustered with distinct gene signatures according to the breast cancer molecular subtype. VDJView has been tested in lab meetings and peer-to-peer discussions, showing effective data generation and discussion without the need to consult bioinformaticians.
**Conclusions**
VDJView enables researchers without profound bioinformatics skills to analyse immune scRNA-seq data, integrating and visualising this with clonality and metadata profiles, thus accelerating the process of hypothesis testing, data interpretation and discovery of cellular heterogeneity. VDJView is freely available at https://bitbucket.org/kirbyvisp/vdjview."
featured: true
publication: "*BMC Medical Genomics*"
url_pdf: "https://bmcmedgenomics.biomedcentral.com/articles/10.1186/s12920-020-0696-z"
doi: "10.1186/s12920-020-0696-z"
---

