# CampyToolBox
## Introduction
`CampyToolBox` is a package for Campylobacter-specific bioinformatic analysis. Currently, it offers the ability to:
1. Predict antimicrobial resistance profiles (AMR), given a *Campylobacter* genome in FASTA format. Specifically, the Beta-Lactam resistance phenotype prediction is optimized for *Campylobacter*, in which the transcriptional activity of *OXA-61*-like-genes, which is previously reported [to be controlled by a SNP in the promoter region](https://www.ncbi.nlm.nih.gov/pubmed/24408987), will be predicted.
2. Annotate a *Campylobacter* genome using Bakta, using NCTC-11168 genes as reference sequence. If a match exist, the gene will be marked as the homolog of a NCTC-11168 gene (eg. *Cj0001*). Virulence and AMR genes will be marked. Plasmids will be summarized and classified.
3. Mark and summarize phase variation sites, given a *Campylobacter* genomic annotation in long GFF3 format (annotation + FASTA).
4. Predict LOS, Penner serotype, flagella types and MLST. 
