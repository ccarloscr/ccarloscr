## Hi 👋, I'm Carlos Camilleri

I am a **geneticist and bioinformatician** with a PhD in Genetics and an MSc in Bioinformatics & Biostatistics, with hands-on experience building and maintaining reproducible workflows for **RNA-seq, ATAC-seq, ChIP-seq, and Hi-C** analysis in **SLURM-based HPC environments**.

My background is in collaborative academic research, where I worked at the interface of **computational and experimental biology**. In practice, this meant designing analyses, building pipelines, integrating multi-omics datasets, and translating results into biologically meaningful conclusions.

I am currently strengthening the **software engineering / data pipeline** side of my profile while applying for roles in **bioinformatics, bioinformatics engineering, and scientific data analysis**.

---

## :microscope: What I work on

- **NGS pipeline development** with **Nextflow**, Bash, and HPC execution
- **Bulk omics analysis**: RNA-seq, ATAC-seq, ChIP-seq, Hi-C
- **Multi-omics integration** for regulatory genomics
- **R-based statistical analysis** with Tidyverse and Bioconductor
- **Python-based ETL/data workflows** for genomics datasets
- Reproducible research practices: documentation, environment management, workflow standardization

---

## :dna: Featured repositories

### [chip-nf](https://github.com/ccarloscr/chip_nf)

**Nextflow DSL2 pipeline** for end-to-end ChIP-seq analysis. Modular architecture covers paired-end QC (fastp and FastQC), Bowtie2 alignment, MACS2 peak calling in narrow/broad mode, consensus peak merging with BEDtools, DESeq2 differential peak analysis, HOMER annotation, PCA, deepTools heatmaps, volcano plots and aggregated multiQC reporting.
Per-module conda environments and local/SLURM execution profiles.

**Focus:** Nextflow, ChIP-seq, Conda, SLURM-HPC, fastp, Bowtie2, MACS2, HOMER, DESeq2

---

### [PyGDC-RNA-ETL](https://github.com/ccarloscr/PyGDC-RNA-ETL)
**Python ETL pipeline** for extracting, transforming, and integrating RNA-seq expression data and clinical metadata from the **NCI Genomic Data Commons**.
Designed to support cohort construction, AJCC stage normalization, somatic mutation annotation, and production of analysis-ready count matrices for differential expression and machine-learning workflows.

**Focus:** Python, ETL, public cancer genomics data, metadata integration

---

### [loopstrength](https://github.com/ccarloscr/loopstrength)
R/Python workflow for **quantifying chromatin loop strength changes** between two Hi-C conditions. Generates size- and distance-matched random loop controls, fetches contact counts via Cooler, computes log-transformed fold changes with empirical two-sided p-values derived from the null distribution and applies Benjamini-Hochberg FDR correction. Outputs a results TSV file and a volcano plot.

**Focus:** Hi-C, 3D genomics, empirical null, low-replicates

---

### [parastar](https://github.com/ccarloscr/parastar)
Containerized batch **RNA-seq alignment pipeline using STAR and GNU Parallel**. Single configuration file with no script editing required.
Features include automated genome index generation, dry-run mode, skip-completed logic for resumable HPC runs, and Apptainer/Singularity image distributed via Zenodo. Includes a SLURM submission wrapper and structured per-sample log output.

**Focus:** RNA-seq, STAR, GNU Parallel, Apptainer/Singularity, SLURM-HPC

---

##  :hammer_and_wrench: Technical skills

**Languages & scripting**  
- **Python**: pandas, numpy, requests, pytest
- **R**: Tidyverse, Bioconductor, ggplot2  
- **Bash**: workflow scripting and HPC execution
- **Nextflow**: DSL2 channels, processes and modules

**Workflow & infrastructure**  
- Nextflow DSL2 modules
- SLURM HPC environments
- Apptainer / Singularity
- Conda / Mamba  
- Linux / Unix  

**NGS / genomics**  
- RNA-seq / ChIP-seq / ATAC-seq
- Hi-C / 3D genomics
- Multi-omics integration  
- QC, differential analysis, regulatory genomics  

**Tools I have worked with**  
- **Primary Processing:** STAR, Bowtie2, Salmon/Kallisto, samtools, fastp/Trimmomatic, FastQC/MultiQC
- **Downstream Analyses:** featureCounts, DESeq2, MACS2, HOMER/ChIPseeker, TADbit, Cooler, deepTools, ggplot2
- **Databases and Portals:** IGV, BioMart, Ensembl, GEO, GDC, UCSC

---

## 📊: About this GitHub

Most repositories here were built to solve real research problems in a research lab setting where I was often the main person developing bioinformatics workflows and analysis utilities. They are portable, reusable and aligned with software engineering best practices.

---

## 📚: Publications

Selected publications from my research work:

- **Camilleri-Robles, C.**, et al. (2024). *Long non-coding RNAs involved in Drosophila development and regeneration*. **NAR Genomics and Bioinformatics**
- **Camilleri-Robles, C.**, et al. (2024). *A shift in chromatin binding of phosphorylated p38 precedes transcriptional changes upon oxidative stress*. **FEBS Letters**
- **Camilleri-Robles, C.**, et al. (2022). *Genomic and functional conservation of lncRNAs: lessons from flies*. **Mammalian Genome**
- Llorens-Giralt, P., **Camilleri-Robles, C.**, et al. *3D genome organization in tissue regeneration: functional requirement of long-range chromatin loops*. **Science Advances** (in press)

Full publication list: [ORCID](https://orcid.org/0000-0001-7103-8354)

---

## :mailbox: Connect

- **Mail:** camilleri.robles@gmail.com
- **ORCID:** [0000-0001-7103-8354](https://orcid.org/0000-0001-7103-8354)
- **GitHub:** [ccarloscr](https://github.com/ccarloscr)
- **Location:** Barcelona, Spain
