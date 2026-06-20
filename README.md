## Carlos Camilleri-Robles, PhD

**Bioinformatics Engineer  |  Barcelona, Spain**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/carloscamilleri/)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0000-0001-7103-8354)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:camilleri.robles@gmail.com)

I build reproducible, production-grade bioinformatics pipelines for multi-omics data, from raw NGS reads to documented, reusable analytical tools. Background in Nextflow DSL2, SLURM HPC, and multi-omics integration, with a PhD in Genetics and an MSc in Bioinformatics and Biostatistics.

---

## :microscope: What I build

- **NGS Pipelines** | Nextflow DSL2 · SLURM · Apptainer/Singularity · Conda
- **Multi-Omics Analysis** |  RNA-seq · ATAC-seq · ChIP-seq · Hi-C · WES
- **Data Engineering** | Python ETL · API integration · count matrix production
- **Statistical Methods** | Differential analysis · empirical null models · FDR · ML
- **Reproducibility** | Containerized workflows · SOP documentation · FAIR practices

---

## :dna: Featured projects

### [chip-nf](https://github.com/ccarloscr/chip-nf) - End-to-end ChIP-seq pipeline
Nextflow DSL2 pipeline covering the full ChIP-seq workflow: `QC → alignment → peak calling → differential analysis → annotation → visualization`. Per-module Conda environments, SLURM and local execution profiles. Single command to go from raw reads to annotated differential peaks and MultiQC report.

`Nextflow` `Bowtie2` `MACS2` `DESeq2` `HOMER` `deepTools` `SLURM` `Conda`

---

### [PyGDC-RNA-ETL](https://github.com/ccarloscr/PyGDC-RNA-ETL) - Clinical genomics ETL pipeline
Python ETL pipeline for large-scale extraction and integration of RNA-seq data and clinical metadata from the NCI Genomic Data Commons. Parallelized batched API downloads with auto-resume, AJCC stage normalization, somatic mutation annotation, and analysis-ready output for DE and ML workflows.

`Python` `ETL` `GDC API` `pandas` `clinical metadata` `cancer genomics`

---

### [parastar](https://github.com/ccarloscr/parastar) - Containerized batch RNA-seq alignment
STAR + GNU Parallel pipeline packaged as an Apptainer/Singularity image (distributed via Zenodo). Single config file, no script editing, dry-run mode, skip-completed logic for resumable HPC runs. Designed for batch processing at scale.

`STAR` `GNU Parallel` `Apptainer` `Singularity` `SLURM` `HPC`

---

### [loopstrength](https://github.com/ccarloscr/loopstrength)  — Hi-C chromatin loop quantification
R/Python framework for quantifying chromatin loop strength changes between conditions. Implements size- and distance-matched random controls, empirical two-sided p-values, and BH-FDR correction. Used in a *Science Advances* publication.

`R` `Python` `Hi-C` `Cooler` `empirical null` `3D genomics`

---

##  :hammer_and_wrench: Stack

| | |
|---|---|
| **Languages** | Python · R · Bash · Nextflow DSL2 · SQL |
| **Workflow** | Nextflow DSL2 · SLURM HPC · Apptainer/Singularity · Conda/Mamba · Git |
| **NGS Tools** | STAR · Bowtie2 · MACS2 · HOMER · DESeq2 · GATK · Cooler · samtools · deepTools · FastQC/MultiQC |
| **Python libs** | pandas · numpy · requests · matplotlib · scikit-learn |
| **R libs** | Tidyverse · Bioconductor · ggplot2 · Seurat |
| **ML / Stats** | PCA · UMAP · random forest · k-means · empirical permutation · BH-FDR |
| **Databases** | GEO · GDC/TCGA · Ensembl · UCSC · BioMart |

---

## 📚: Selected publications

- **Camilleri-Robles, C.**, et al. (2024). Long non-coding RNAs involved in *Drosophila* development and regeneration. *NAR Genomics and Bioinformatics*
- **Camilleri-Robles, C.**, et al. (2024). A shift in chromatin binding of phosphorylated p38 precedes transcriptional changes upon oxidative stress. *FEBS Letters*
- Llorens-Giralt, P., **Camilleri-Robles, C.**, et al. 3D genome organization in tissue regeneration involves long-range chromatin loops. *Science Advances* (in press)

Full publication list: [ORCID](https://orcid.org/0000-0001-7103-8354)

---
