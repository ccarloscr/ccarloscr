## Carlos Camilleri-Robles, PhD

**Bioinformatics · Scientific Computing |  Barcelona, Spain**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/carloscamilleri/)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat&logo=orcid&logoColor=white)](https://orcid.org/0000-0001-7103-8354)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:camilleri.robles@gmail.com)

I build reproducible bioinformatics pipelines and multi-omics workflows for biomedical and translational research. Background in multi-omics integration (RNA-seq, ATAC-seq, ChIP-seq, Hi-C, WGS/WES), statistical modelling, and machine learning for biomarker discovery, with a PhD in Genetics and an MSc in Bioinformatics and Biostatistics. Experienced in Nextflow DSL2, Snakemake, SLURM HPC, Apptainer/Singularity and Docker, with a strong focus on workflow reproducibility, FAIR principles, SOP documentation, and supporting multidisciplinary research teams.

---

## :microscope: What I build

- **NGS Pipelines** | Nextflow DSL2 · Snakemake · SLURM-HPC · AWS (S3/EC2) · Apptainer/Singularity · Docker · Conda
- **Multi-Omics Analysis** |  RNA-seq · scRNA-seq · ATAC-seq · ChIP-seq · Hi-C · WGS/WES
- **Biomarker Discovery** | ML-driven biomarker stratification · statistical modelling · multi-omics integration
- **Statistical Methods** | Differential expression (DESeq2) · dimensionality reduction · multivariate analysis · empirical null models
- **Reproducibility** | Git version control · containerized workflows · SOP documentation · FAIR principles

---

## :dna: Featured projects

### [MALEXA](https://github.com/ccarloscr/malexa) - Machine learning for clinical biomarker discovery
Snakemake ML pipeline predicting somatic mutation status from bulk RNA-seq expression data, directly applicable to expression-based biomarker stratification. Validated on TCGA-LUAD (n=517) with leakage-free cross-validation, within-fold normalization, and benchmarking of ElasticNet and XGBoost, achieving >0.82 ROC-AUC for EGFR/KRAS mutations. Cross-fold gene importance consensus identifies candidate expression biomarkers for downstream investigation.

`Machine Learning` `Clinical Biomarkers` `Snakemake` `Python` 


### [chip-nf](https://github.com/ccarloscr/chip-nf) - End-to-end ChIP-seq pipeline
Nextflow DSL2 pipeline covering the full ChIP-seq workflow: `QC → alignment → peak calling → differential analysis → annotation → visualization`. Per-module Conda environments, SLURM and local execution profiles. Single command to go from raw reads to annotated differential peaks and MultiQC report.

`Nextflow` `Bowtie2` `MACS2` `DESeq2` `HOMER` `deepTools` `SLURM` `Conda`

---

### [parastar](https://github.com/ccarloscr/parastar) - Containerized batch RNA-seq alignment
STAR + GNU Parallel pipeline packaged as an Apptainer/Singularity image (distributed via Zenodo). Single config file, no script editing, dry-run mode, skip-completed logic for resumable HPC runs. Designed for batch processing at scale.

`STAR` `GNU Parallel` `Apptainer` `Singularity` `SLURM` `HPC`

---

### [PyGDC-RNA-ETL](https://github.com/ccarloscr/PyGDC-RNA-ETL) - Clinical genomics ETL pipeline
Python ETL pipeline for large-scale extraction and integration of RNA-seq data and clinical metadata from the NCI Genomic Data Commons. Parallelized batched API downloads with auto-resume, AJCC stage normalization, somatic mutation annotation, and analysis-ready output for DE and ML workflows.

`Python` `ETL` `GDC API` `pandas` `clinical metadata` `cancer genomics`

---

### [loopstrength](https://github.com/ccarloscr/loopstrength)  — Hi-C chromatin loop quantification
R/Python framework for quantifying chromatin loop strength changes between conditions. Implements size- and distance-matched random controls, empirical two-sided p-values, and BH-FDR correction. Used in a *Science Advances* publication.

`R` `Python` `Hi-C` `Cooler` `empirical null` `3D genomics`

---

##  :hammer_and_wrench: Stack

| | |
|---|---|
| **Languages** | Python · R · Bash · SQL |
| **Workflow** | Nextflow DSL2 · Snakemake · SLURM · AWS · Apptainer/Singularity · Docker · Conda/Mamba · Git |
| **NGS Tools** | STAR · Bowtie2 · MACS2 · HOMER · DESeq2 · GATK · Cooler · samtools · deepTools · FastQC/MultiQC |
| **Python libs** | pandas · numpy · requests · matplotlib · scikit-learn |
| **R libs** | Tidyverse · Bioconductor · ggplot2 · Seurat · RMarkdown |
| **Machine Learning** | PCA/UMAP · k-means/hierarchical clust. · SVMs · ElasticNet · Random forest · XGBoost |

---

## :books: Selected publications

- Llorens-Giralt, P., **Camilleri-Robles, C.**, et al. (2026) 3D genome organization in tissue regeneration involves long-range chromatin loops. *Science Advances*
- **Camilleri-Robles, C.**, et al. (2024). Long non-coding RNAs involved in *Drosophila* development and regeneration. *NAR Genomics and Bioinformatics*
- **Camilleri-Robles, C.**, et al. (2024). A shift in chromatin binding of phosphorylated p38 precedes transcriptional changes upon oxidative stress. *FEBS Letters*


Full publication list: [ORCID](https://orcid.org/0000-0001-7103-8354)

---
