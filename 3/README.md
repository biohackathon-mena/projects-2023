# Project 3

## Title:

Embedding ontologies 

## Description:

The main objective of the proposed project is to generate realistic
synthetic patients health data by embedding existing human knowledge
(such as ontologies) into advanced deep generative model (Conditional
Generative Adversarial Network models). We will integrate, for the
first time, human knowledge (represented by ontologies), deep learning
(Generative Adversarial Networks), Zero-Shot Learning, and
privacy-preserving methods (Differential Privacy) in one generative
framework. The primary use case we would like to apply in the
Bio-hackathon is to generate synthetic health data for rara disease
patient. Rare Diseases (incidence <1 in 2000) are life-threatening or
chronically debilitating from early childhood and impose challenging
social and economic burdens. The extreme heterogeneity and complexity
of RDs and the sparsity of the available data cause difficulty in
setting up research activities, delivering timely diagnosis and
treatments (taking years and large costs to get correct
diagnoses). Therefore, our motivation is to accelerate rare disease
research and promote patients' well-being by generating more realistic
patient data with both seen and unseen classes based on existing human
knowledge and limited data.

To be more specific, beyond learning from data, we will embed rare
disease ontological models from such as Orphanet
(https://www.orpha.net/consor/cgi-bin/index.php) or other exiting rare
disease ontologies from MENA as conditional vectors into the
generative model (GANS). The generative model 1) generates data that
is structurally and statistically similar to the real seen data (deep
learning), 2) generates data belonging to unseen classes or relations
which are not observed in the real data, but represented in the
ontologies (ontology embeddings). Then, we will 3) predict new classes
that were not observed during training using zero-shot learning model,
4) add differetial privacy in the generative model to protect
individual’s identity and provide privacy measure.

We have experience in building GANs model, privacy-preserving methods,
and started integrating ontology embeddings into GAN models. (Paper:
https://arxiv.org/abs/2206.13787
Repo:https://github.com/sunchang0124/dp_cgans). To move this research
project forward, we would like to implement the idea in the
Bio-Hackathon and attract competent and experienced researchers and
developers working with us to achieve the goal.

## Theme:

machine learning and AI methods

## Team leader:

 * Name: Chang Sun
 * Contact: chang.sun@maastrichtuniversity.nl
 
## Submission number:

13
