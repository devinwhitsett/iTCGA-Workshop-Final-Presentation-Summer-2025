Data Links : https://www.ncbi.nlm.nih.gov/sra?term=SRP557307
## Nitric Oxide (NO) and its Role in Detecting Diseases: ITCGA Summer Workshop Project

Hello! This project is part of the **Summer ITCGA Workshop at UMass Boston**, in collaboration with **Dana-Farber: Integrated Training in Computational Genomics and Data Sciences**.

###  Project Overview
- NO production significantly shapes IFN-y induced reprogramming in macraphapes **white blood cells (WBCs)**.
- IFN-y increases NO and lactate levels while reducing macrophage survival  **Blocking NO reverses these effects**, IFN-y also boosts:
  - NAD+ producing genes linking metabolism to immune activity
  - Inhibits NAD+ pathways to lower NO and improve survival 
- Overall Role:
  - Connecting IFN-y signals and metablism
  - Regulates gene expression into a coordinated immune response
- This study explores the genomic effects of Nitric Oxide as a **biomarker**.
  - Key gene expression changes linked to diseases such as cancer, ashtma, and autoimmune disorders
  - Implicated 3 protein hubs in the PPI network, STAT1, IRF7, IRF1, that play a big role in shaping the immune landscape through upregulated gene expression

### RNA-seq Analysis Pipeline on Chimera Cluster

- **Download FastQ Files**
  - Used sratoolkit and a custom fastq-dump.sh script to download sequencing data from SRA

- **Quality Control**
  - Assessed read quality using FastQC

- **Adapter Trimming**
  - Removed Illumina adapters and low-quality bases using cutadapt
  - Employed SLURM scripts for batch trimming

- **Data Alignment & Expression Analysis**
  -Next steps include:
    - Aligning reads to a reference genome
    - Quantifying gene expression


