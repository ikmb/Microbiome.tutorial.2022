# Microbiome tutorial 2022

## Summer School "Frontiers in Microbiome Research""

Instructors: Eike Matthias Wacker (e.wacker@ikmb.uni-kiel.de), Malte Rühlemann (m.ruehlemann@ikmb.uni-kiel.de)
Co-author of the scripts: Lucas Moitinho-Silva (l.silva@ikmb.uni-kiel.de)

## Description

Sequencing processing in microbiome projects generally results in an abundance table, which typically
includes the number or proportion of microbial features found in each sample. In a hands-on manner,
participants will be guided to analyze an example dataset (based on 16S rRNA gene) in terms of alpha and
beta diversity, and taxonomic features. The level of the workshop is basic, therefore, no prior knowledge is
necessary. However, participants are required to bring their own laptop to the workshop. R and Rstudio will
be used, therefore, participants are expected to have them installed prior to the course.

## Preparation

Read the attached article:

* Workshop 1 - Liu et al. - [A practical guide to amplicon and metagenomics analysis of microbiome data](http://www.protein-cell.org/en/article/doi/10.1007/s13238-020-00724-8)

## Requires

Tutorial performed on a:

 - R version 3.6.3 (2020-02-29)
 - Platform: x86_64-pc-linux-gnu (64-bit)
 - Running under: Ubuntu 18.04.5 LTS

A guide to install all necessary packages for R can be found in the `scripts/install.packages.in.R.R` script.

Main packages:  

 - dada2_1.12.1
 - phyloseq_1.28.0
 - tidyverse_1.2.1
 - vegan_2.5-5
 - microbiome_1.11.2
 - DESeq2_1.24.0

## References

This material was based on [phyloseq tutorials](https://joey711.github.io/phyloseq/), including the [Bioconductor workflow for microbiome data analysis](https://f1000research.com/articles/5-1492/v2)
