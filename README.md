# Repository for Workshop Course Homeworks in Bioinformatics Institute

<img src="https://github.com/iliapopov17/BI-Workshop-miniProjects/blob/main/imgs/workshop_light.png#gh-light-mode-only" width = 50%/>
<img src="https://github.com/iliapopov17/BI-Workshop-miniProjects/blob/main/imgs/workshop_dark.png#gh-dark-mode-only" width = 50%/>

> This repository for **Workshop Course *Homeworks*** in *Bioinformatics Institute 2023-2024*

## Project 9. scRNA-seq
For [Project 9](Project_09) CITE-seq was used to perform a comprehensive single-cell analysis of human bone marrow. Utilizing `Scanpy`, the study processed a dataset of 33,454 cells, identifying eight distinct cell groups. Focus was given to monocytes and myeloid dendritic cells, characterized by specific gene markers such as FCN1, VCAN, AIF1, SPI1, and CD68.

## Project 8. RepSeq Sudoku

For [Project 8](Project_08) we delved into the intricacies of T-cell receptor β-chain repertoire diversity across CMV+ and CMV- donors. Utilizing `RepSeq` analysis, 16 TCRB samples were annotated.

## Project 7. Dead Man's Teeth

For [Project 7](Project_07) we investigated the microbial communities in ancient dental calculus samples.
Pipeline using `QIIME2` was applied to analyse 16s rRNA amplicon sequencing data.
The `Standard` database in `Kraken2` was used for metagenomic profiling of Shotgun Sequencing data, and `Pavian` was used to visualise the results. The _Tannerella forsythia_ genome was downloaded from the `NCBI` database using the `entrez-direct` package, and the `bwa` algorithm was used to index it and then align metagenomic contigs to it. The `samtools` was used to compress, sort and index the reads aligned to the reference. The `bedtools` was used to find intersections of the alignment with the genome annotation file.

## Project 6. Baking Bread

For [Project 6](Project_06) we explored _Saccharomyces cerevisiae_ transcriptome dynamics during a 30-minute anaerobic fermentation.<br>
Used RNA-seq and `HISAT2`, `featureCounts`, `DESeq2` for alignment, quantification, and differential expression analysis. Identified 1905 significant genes, revealing upregulation in glycerol biosynthesis and glucose transport. To determine the primary biological processes involving differentially expressed genes used `goSlipMapper` and `ShinyGO`

## Project 5. "H+"

For [Project 5](Project_05) we performed genotyping and SNP annotation of human 23andMe project data.<br>
During the project we analysed data from 23andMe test of our teacher in Bioinformatics. We used `plink` to convert the raw data to `vcf` format. Haplogroup identification was performed with `mthap` for mtDNA and `Y-SNP Subclade Predictor` + `YSEQ Clade Finder` for Y-chromosome. SNPs were annotated with `SnpEff` with Human Reference Genome build 37. To compare obtained data with the ClinVar database we used `SnpSift`. Further SNP analyses were carried out using `SNPedia` database.

## Project 4. Eukaryotic genomes: Tardigrades

For [Project 4](Project_04) we performed tardigrade *Ramazzottius varieornatus* genome annotation and protein function prediction.<br>
During the project we used precomputed `AUGUSTUS` results, including `fasta` and `GFF` files to perform a structural annotation of *Ramazzottius varieornatus* (strain YOKOZUNA-1) genome. To localise proteins associated with DNA we performed a local alignment-based search with `blastp`. Subcellular localization predictions were made with `WoLF PSORT` and `TargetP`. To identify homologous sequences we used `BLAST` search against the `UniProtKB/Swiss-Prot` database. To identify protein domains and motifs in the selected protein sequences we performed `pfam` predictions with `HMMERz` and `Pfam` databases.


## Project 3. De novo sequencing. *E.coli* outbreak investigation

For [Project 3](Project_03) we did de novo assembly of its genome. Data is lost. Details to be disclosured soon.

## Project 2. Deep Sequencing

For [Project 2](Project_02) we did variant calling of deep sequencing data (*Influenza A virus* (H3N2) hemagglutinin gene).<br>
During the project we also used `FastQC`, `Trimmomatic`, `bwa`, `samtools` and `VarScan`, but this time we used `Snakemake` script to make automatisation. For data visualisation `IGV` was used

## Project 1. Alignment to reference, variant calling

For [Project 1](Project_01) we did variant calling of *Escherichia coli* WGS.<br>
During the project we did data preprocessing with `FastQC` and `Trimmomatic`, then we mapped trimmed reads to a large reference genome with `bwa`, generated `mpileup` file using `samtools` and performed variant calling with `VarScan`
