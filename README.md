# Hi, I'm Griffin Kramer

**Bioinformatics researcher** building NGS analysis pipelines across RNA-seq, ChIP-seq, Hi-C, and CRISPR genomics.  
MSc Molecular Biosciences (Bioinformatics) · University of Bath · US & UK citizen based in the SF Bay Area.

## About Me

I work at the intersection of computational biology and genomics, taking raw sequencing data and building reproducible pipelines that extract biological meaning from it. My background spans academic research labs globally, with experience across a wide range of NGS assay types and analytical frameworks.

Currently finishing my MSc at Bath, where I've been analyzing Hi-C data to map 3D genome organization in parasitic nematodes (Hunt Lab) and building multi-omics RNA-seq workflows integrating variant calling outputs (Taylor Lab).

Before that, I spent three years as an undergraduate researcher at UCSB's College of Creative Studies, a highly selective, research-intensive honors college, where I built CRISPR screen analysis pipelines and engineered MOTREC, a ChIP-seq pipeline for mapping CRISPR off-target binding events.


## Featured Projects

### [MOTREC](https://github.com/GriffinKramer/MOTREC)
Python CLI tool for annotating ChIP-seq peaks with nearest genomic features, phenotype scores, and GO terms. Built to map CRISPR on/off-target binding events in transcription regulation experiments.
<br> `Python` `ChIP-seq` `MACS3` `Gene Ontology` `CRISPRi`

### [σ⁵⁴ Regulatory Rewiring Analysis](https://github.com/GriffinKramer/Regulatory-Rewiring)
Full R analysis pipeline for a study of transcriptional rewiring in *Pseudomonas fluorescens*. Covers DESeq2 differential expression, FGSEA pathway enrichment, Spearman correlation, UpSet plots, and WGS variant calling. Data available on SRA: PRJNA992893.  
`R` `DESeq2` `fgsea` `ggplot2` `bcftools` `minimap2`

### [STEC Geographic Source Attribution](https://github.com/GriffinKramer/Microbial-Genomics-ML)
Machine learning pipeline for predicting country and region of origin of Shiga-toxigenic *E. coli* (STEC) from whole genome sequencing kmer data. Evaluates Random Forest, GBDT, and LinearSVC across preprocessing parameter conditions including UK class capping, chi-squared feature selection, and random oversampling. Final models trained on 2014-2018 data and evaluated on a held-out 2019 test set.
<br> `Python` `scikit-learn` `imbalanced-learn` `Random Forest` `GBDT` `LinearSVC` `WGS`

### [NGS Variant Calling Pipeline](https://github.com/GriffinKramer/RP1B)
Nextflow pipeline supporting two modes: simulate mutations + reads from a reference genome, or run real paired-end reads through alignment, dual variant calling (bcftools + Snippy), and VCF benchmarking.  
`Nextflow` `Python` `minimap2` `bcftools` `Snippy` `samtools`

### [CRISPR Screen & Genomics Utilities](https://github.com/GriffinKramer/BFM)
Python toolkit for CRISPRi screen processing, MAGeCK analysis, CRISPR off-target mapping, and proteomics integration.
<br> `Python` `pandas` `MAGeCK` `CRISPRi` `Bowtie2`

### [Burrows-Wheeler Transform](https://github.com/GriffinKramer/Burrows-Wheeler-Transform)
From-scratch Python implementation of the BWT, inverse BWT, and FM-index pattern matching using a custom Wavelet Tree class. The algorithm underpins widely-used sequence aligners including Bowtie2 and BWA. <br> `Python` `JupyterLab` `Object-Oriented-Programming` `Algorithms` `Sequence-Alignment`

## Skills

**Languages:** Python · R · Bash · Java · C  
**NGS Tools:** Bowtie2 · STAR · SAMtools · MACS2/3 · MAGeCK-iNC · minimap2  
**Assays:** Bulk RNA-seq · scRNA-seq · ChIP-seq · Hi-C · CRISPRi screens · Variant calling  
**Analysis:** DESeq2 · fgsea · GSEA · Multi-omics integration · 3D genome organization · ML methods  
**Environment:** Unix/Linux · HPC · Git · Nextflow · Reproducible pipeline development  


## Recognition

NSF Graduate Research Fellowship Program — Honorable Mention, Genomics (2025)  
Dean's Award for Academic Excellence · Faculty Discretionary Merit Scholarship — University of Bath (2025)

[griffinkramer@gmail.com](mailto:griffinkramer@gmail.com) · [LinkedIn](https://www.linkedin.com/in/griffin-d-kramer) · SF Bay Area, CA
