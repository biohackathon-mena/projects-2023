# Project 15

## Title:

Resources for genome workflows in the MENA population

## Description:

Validated and accurate bioinformatics workflows crucially rely on
reference resources such as reference genomes, population-specific
allele frequencies, etc. Few such resources have been made publicly
available for the population in the MENA region. The aim of this
project is to
* collect population-specific genomic resources
* combine them into a genome graph
* design a variant calling workflow to use this genome graph as
  reference
* extend the workflow to other data types

Relevant resources to use as part of this project are derived from the
Qatar Genome Program, the UAE population genomics projects, Kuwait
genome program, and the Saudi Genome Program.

The project will be split in the following tasks:
1. Collect genomic resources, including
  * https://github.com/bio-ontology-research-group/KSA001
  * https://www.ncbi.nlm.nih.gov/bioproject/PRJNA290484
  * https://www.ncbi.nlm.nih.gov/sra/SRX535330[accn]

2. Generate genome graph
  * using https://github.com/vgteam/vg
  
3. Modify existing, validated variant calling workflow to use genome
   graph as reference
  * Use VG Toolkit (https://github.com/vgteam/vg), HISAT2, etc.
  
4. Evaluate workflow
  * using public exome or genome data from MENA populations

## Theme:

* workflows

## Team leader:

 * Name: Robert Hoehndorf
 * Contact: robert.hoehndorf@kaust.edu.sa
 

