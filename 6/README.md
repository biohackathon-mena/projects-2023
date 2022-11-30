# Project 6

## Title:

Improving prokaryotic genome annotation through an interoperable and
multi-platform bioinformatic pipeline.

## Description:

Genome annotation is a complex task with as many problems as there are methods to carry it out. In a recent study, we identified a number of shortcomings apparent to all prokaryotic annotation tools (https://academic.oup.com/bioinformatics/article/38/5/1198/6454948).  
I am currently developing an annotation tool that is designed to
specifically look for the types of genes routinely missed by
state-of-the-art techniques without overwriting the hard work already
done by others
(https://www.biorxiv.org/content/10.1101/2022.03.31.486628v3 - In
review with NAR).  We do this by specifically only looking for genes
'between' currently annotated genes, that are missing from both
canonical and novel annotations.  My tool, StORF-Reporter, is
available as a Python package via pip and it is interoperable with
PROKKA and some other tools but is still not as accessible to non-core
bioinformaticians as it could be.

I believe that developing this software further to be interoperable with more tools and to make it available on platforms such as Galaxy, Anaconda and as an independent web service, where users could simply upload multiple genome annotation files and receive a list of novel gene predictions, would significantly increase both its usefulness and accessibility.
Most importantly, we would also want to allow for the native and seamless transfer of the novel gene predictions to contemporary bioinformatic tools to allow further analysis, such as; function prediction, pangenomic analysis, taxonomic lineage identification and structural prediction, would significantly improve its usefulness and scope.
Lastly, StORF-Reporter has been shown to predict a high number of novel genes, those without homology to any sequence database, but which share high levels of conservation across genera. Therefore, a database resource could be setup to house these sequences to ensure that they are accessible for future investigation.

## Theme:

bioinformatics software

## Team leader:

 * Name: Nicholas Dimonaco
 * Contact: dimonacn@mcmaster.ca
 
## Submission number:

27
