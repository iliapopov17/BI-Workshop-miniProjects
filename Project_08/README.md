# T-cell receptor diversification and specialisation: analysis of β-cell repertoire and phenotypic characterisation in response to cytomegalovirus

## Abstract
T-lymphocytes differentiated from haematopoietic stem cells are key elements of the adaptive immune response. These cells contribute to immune-mediated cell death through two subclasses: CD4+ and CD8+, which function as "helpers" and "killers" (cytotoxic), respectively [^1]. The uniqueness of T-lymphocytes is due to the presence of specific T-cell receptors (TCR) localised on their surface. In the process of T-cell differentiation in the thymus, somatic rearrangement of V, D and J genes belonging to the TR locus genome occurs. The TCR complementarity-determining regions (CDRs) and immunoglobulin (antibody) variable chains are the most variable regions critical for the diversity of antigenic specificities generated by lymphocytes [^2]. Divergence of these regions can be assessed by next generation sequencing (NGS) of adaptive immune receptor rearrangements (RepSeq) expressed in the lymphocyte population [^3], [^4].

## Introduction
Within this study, a total of 16 T-cell receptor β-chain repertoire samples from two individual donors, one of whom was seropositive for cytomegalovirus (CMV+), were analysed. The TCR β-chain repertoire was subjected to sequencing using the 5'-RACE method, revealing a diversity of antigen-specific receptors. T-lymphocytes were classified according to their CD4+ or CD8+ subclasses and phenotypic characteristics, either naive or memory. Two independent blood samples were obtained for each donor/population/phenotype combination, ensuring repeatability and reliability of the data. Clonotypic frequencies were determined by analysing 10,000 sequenced reads for each of the samples, facilitating accurate quantification of the TCR repertoire [^5].
The aim of the present study is to reconstruct sample metadata and identify duplicate combinations. This involves annotating samples (s1 – s16), labelling the corresponding donor, population, and phenotype where applicable.

## Materials and Methods
To analyse the heterogeneity of the T-cell receptor repertoire and annotation results, a complex sample metadata recovery scheme was applied [^6]. This scheme involves systematic identification and labelling of samples (s1 – s16), matching them to relevant donors, populations, and phenotypes, and identifying and eliminating potential duplicates in the data.
•	To determine the T-cell population, a heat map of CDR3 utilisation was used to categorise the samples into two distinct groups.
•	Phenotypic characterisation was performed by analysing correlation patterns between samples. 
•	Donor samples were identified using a correlation heat map.
•	To determine CMV status, an analytical work-up was performed using an antigenic profile histogram.

## Results
### T-cell populations
Groups in Figure 1 show differences in CDR3 utilisation profile, indicating that they belong to different T-cell subclasses. Repertoire annotation performed using the CD8 TRB sequence database provided a higher level of annotation for one of the groups. In addition, pairs of samples were identified and grouped based on similarities in the CDR3 utilisation heatmap, which may facilitate the identification of overlapping replicates in the data.

### Phenotypic characterisation
Figure 2 revealed four pairs of samples with high positive correlation, indicating a specialised response of these cells to a particular antigen. In contrast, the remaining pairs of samples showed significantly lower levels of correlation in the TCR β-chain repertoire, which may indicate their relative naivety or lack of specialisation.

### Donor samples
Analysis of the dendrogram on Figure 2 showed that T cell subtypes form four clusters that divide the axes in half. Given that clustering is not related to population or phenotype, it can be assumed that samples within each cluster belong to a single donor.

### CMV status
Figure 3 demonstrated that the s3 and s7 CD8 samples belonged to a CMV positive donor. In addition, samples from donors without CMV were found to contain sequences capable of recognising CMV in their CDR3 repertoire. Analysis of the HLA allele histogram on Figure 4 revealed a group of samples with the B*07 HLA allele, indicating that they belonged to a single donor confirmed as CMV+.

|Sample|Donor|Subset|Phenotype|CMV|
|------|-----|------|---------|---|
|s3    |D1   |CD8   |memory   |+  |
|s7    |D1   |CD8   |memory   |+  |
|s4    |D2   |CD8   |memory   |-  |
|s6    |D2   |CD8   |memory   |-  |
|s9    |D1   |CD8   |naive    |+  |
|s14   |D1   |CD8   |naive    |+  |
|s11   |D2   |CD8   |naive    |-  |
|s12   |D2   |CD8   |naive    |-  |
|s8    |D1*  |CD4   |memory   |+  |
|s10   |D1*  |CD4   |memory   |+  |
|s1    |D2*  |CD4   |memory   |-  |
|s5    |D2*  |CD4   |memory   |-  |
|s15   |D1*  |CD4   |naive    |+  |
|s16   |D1*  |CD4   |naive    |+  |
|s2    |D2*  |CD4   |naive    |-  |
|s13   |D2*  |CD4   |naive    |-  |

_Table 1. Metadata Summary for TCR β-Chain Repertoire Samples. Asterisks indicate potential donor mismatches for  CD4 samples, necessitating a swap of CMV statuses due to  the inability to conclusively match CD4 and CD8 cells from  the same donor._

<div style='justify-content: center'>
<img src="https://github.com/iliapopov17/BI-Workshop-miniProjects/blob/main/Project_08/imgs/CDR3.png" align='center', width="50%">
</div>

_Figure 1. Heat map of CDR3 utilisation._

<div style='justify-content: center'>
<img src="https://github.com/iliapopov17/BI-Workshop-miniProjects/blob/main/Project_08/imgs/correlation.png" align='center', width="50%">
</div>

_Figure 2.  Correlation patterns between samples._

<div style='justify-content: center'>
<img src="https://github.com/iliapopov17/BI-Workshop-miniProjects/blob/main/Project_08/imgs/antigenic.png" align='center', width="50%">
</div>

_Figure 3. Antigenic profile histogram._

<div style='justify-content: center'>
<img src="https://github.com/iliapopov17/BI-Workshop-miniProjects/blob/main/Project_08/imgs/HLA.png" align='center', width="50%">
</div>

_Figure 4. HLA allele profile histogram._

## Discussion
This study successfully reconstructed metadata for 16 T-cell receptor β-chain repertoire samples. The analysis revealed distinct CDR3 utilization patterns between CD4+ and CD8+ T-cells, enabling population classification. Phenotypic characterization identified potentially antigen-experienced (memory) and naive T-cell subsets.  Interestingly, CMV-specific sequences were detected in both CMV+ and CMV- donors, suggesting potential cross-reactivity or exposure history. However, further investigation is needed to definitively assign CMV status to all samples, particularly for CD4+ cells.


# Supplementary files for project report:

**Files**:
- `BI_Project_8_Popov.pdf`  - report on the project in thesis format
- [`Lab journal`](https://github.com/antigenomics/repseq-annotation-tutorial) - instead of writing my own laboratory journal I've used this tutorial

[^1]: Guo, R. et al. Generation and clinical potential of functional T lymphocytes from gene-edited pluripotent stem cells. Exp. Hematol. Oncol. 11, 27 (2022).
[^2]: Sun, L., Su, Y., Jiao, A., Wang, X. & Zhang, B. T cells in health and disease. Signal Transduct. Target. Ther. 8, 1–50 (2023).
[^3]: Hou, D., Chen, C., Seely, E. J., Chen, S. & Song, Y. High-Throughput Sequencing-Based Immune Repertoire Study during Infectious Disease. Front. Immunol. 7, 336 (2016).
[^4]: Chaara, W. et al. RepSeq Data Representativeness and Robustness Assessment by Shannon Entropy. Front. Immunol. 9, 1038 (2018).
[^5]: Qi, Q. et al. Diversity and clonal selection in the human T-cell repertoire. Proc. Natl. Acad. Sci. 111, 13139–13144 (2014).
[^6]: antigenomics/repseq-annotation-tutorial: 📝 [Tutorial] RepSeq data mining basics in R. https://github.com/antigenomics/repseq-annotation-tutorial.