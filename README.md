# PAMA-seq
Comprehensive Cross-Domain Taxonomic Classification of Microbiotas using Partitioned Amplification Multiplexed Amplicon Sequencing (PAMA-seq)

## Disclaimer:
All jupyter notebooks are provided for reference purpose only. A bioinformatics pipeline for PAMA-seq data analysis is currently under development. The code here is no longer maintained and is provided as is in order for the reader to get a general idea of the bioinformatics processes.

## Abstract
Microbial communities encompass diverse bacteria, archaea, and eukaryotes that play vital roles in ecosystems and host health. Comprehensive analysis of these communities requires accurate, quantitative, and cross-domain profiling, yet current sequencing methods—metagenome shotgun sequencing (MGS) and ribosomal RNA (rRNA) amplicon sequencing—struggle to achieve these goals in a single assay. MGS provides broad functional insights but suffers from high cost, computational burden, and reliance on incomplete reference databases. rRNA amplicon sequencing, while more taxonomically targeted, typically profiles either prokaryotes or eukaryotes separately, depending on the chosen primer sets, and thus lacks simultaneous cross-domain resolution. To address these limitations, we developed PAMA-seq, a droplet-digital multiplex PCR technique. PAMA-seq partitions DNA sample from microbial communities into nanoliter droplets, each containing a single template molecule, and independently amplifies both the 16S and 18S rRNA genes, resulting in uniform amplification efficiency and accurate quantification. We validated PAMA-seq on a synthetic microbial community, a stool sample from a patient with colorectal cancer, and a coastal seawater sample. The method provided stable, cross-domain taxonomic profiles at sequencing depths as low as 10⁴ reads—one to two orders of magnitude fewer than comparable shotgun metagenomics approaches—while significantly reducing variability between replicates. By combining comprehensive domain coverage with low sequencing depth requirements, PAMA-seq offers an efficient, cost-effective, and scalable method for monitoring microbial communities across diverse ecosystems, from clinical samples to global marine environments.

## Contents

code/ (python jupyter notebook for all data analysis)
```
PAMA-seq_Simulation_analysis.ipynb
PAMA-seq_ocean_subsample.ipynb
PAMA-seq_ocean_venn_diagram_R.ipynb
PAMA-seq_zymo.ipynb
PAMA_seq_gut.ipynb
```
data/ (Data for analysis)
```
gut/
ocean/
ocean_subsample/
zymo/
```
output/ (output files after analysis)
```
gut/
ocean/
ocean_subsample/
zymo/
```

## Required Tools

FastP 

Bowtie2 

Samtools 

MetaPhlAn4

BMTagger

Kraken2

GOTTCHA2

Kaiju

CZID.org 

Kbase.us

Python

Seqtk toolkit 


## Data availability
All sequencing data is accessible at the NCBI Sequence Read Archive (Accession numbers: PRJNA1232616).

For Intermediate files and output files, please contact the author: (xli@chem.fsu.edu).


