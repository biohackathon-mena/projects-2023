# Project 7

## Title:

MetaboliteNET: building a metabolite centric knowledge base by
ontology-based mining annotations from literature

## Description:

Recent estimates in dementia cases projected that the largest
increases due to population ageing are observed in east Asia, and
north Africa and the Middle East [1]. There is an increasing body of
scientific evidence on how natural medicines (i.e. herbal medicines,
traditional formulas) and food metabolites are environmental factors
that can be used to maintain health or treat multifactorial and
chronic diseases such as neurodegenerative diseases [2]. For example,
traditional Arabic herbal medicine is a part of modern life in the
Middle East, and it is acquiring worldwide respect, with growing
interest among traditional herbalists and the scientific
community. Traditional medicines represent likely sources of
relatively inexpensive drugs for symptomatic management as well as
potential libraries of new therapeutic approaches. Plants produce a
wide diversity of metabolites that exhibit a wide array of biological
and pharmacological properties. The multitarget activities of many
metabolites can explain the medical application of complex extracts
from medicinal plants, food or even drug metabolites for health
disorders that involve several targets. Therefore, the development of
a metabolite-centric annotation dataset from literature is useful for
the identification of functionally similar metabolites with
application in disease biomarker discovery, drug discovery or
agriculture. Furthermore, Data science pipelines applied on text
mining based knowledge graphs have the potential to accelerate
understanding on mechanisms and mode of actions, link therapies to new
potential target applications, and rapidly accelerate the validation
(and exclusion) of traditional medicines [3].

The motivation of this project is to provide a metabolite-centric
annotation dataset as a valuable knowledge resource to enhance
precision medicine in the MENA region. We propose the development of a
metabolite centric annotation data set, the MetaboliteNET annotation
data set, built from the literature and existing resources for machine
learning prediction of interesting metabolites.

Our proposal is to extract human and plant metabolite annotations from
literature and make them publicly available. We aim at building a
knowledge graph from the metabolite - X annotation data set, where X
will be phenotypes (Human Phenotype Ontology or HPO), diseases (Human
Disease Ontology or DO, and Mondo Disease Ontology or MONDO),
environmental factors (Environment Ontology or ENVO), anatomical
(Uberon multi-species anatomy Ontology or UBERON), Cell types (Cell
Ontology or CL), gene products functions (Gene Ontology or GO) for
human metabolites, and X will be ENVO, CL, phenotypes (Flora Phenotype
Ontology or FLOPO, and Plant Trait Ontology or PTO), anatomy (Plant
Ontology or PO) for plants. The MetaboliteNET annotation data set will
be yielded automatically from mining the literature using an in-house
annotation tool that performs co-occurrence extraction of mentions (as
ontology terms) at abstract level over all MEDLINE, and applies a
statistical approach based on ontological structure to determine the
association strength [4]. This tool is currently being updated to
extract relevant information at mention and publication level. We will
apply the license Creative Commons Attribution 4.0 International to
the annotation data set. We will evaluate our text mined data against
curated associations. The MetaboliteNET annotation data set will serve
as a foundation to build a metabolite-centric knowledge graph for
representation learning or curation for corpora development.


[1] GBD 2019 Dementia Forecasting Collaborators, Estimation of the
global prevalence of dementia in 2019 and forecasted prevalence in
2050: an analysis for the Global Burden of Disease Study 2019, The
Lancet, 7, 2, e105-e125, February 01, 2022,
https://doi.org/10.1016/S2468-2667(21)00249-8 
[2] Emmanuel Ayodeji Ayeni, Yuzhou Gong, Hao Yuan, Yikao Hu, Xiaolin Bai, Xun Liao,
Medicinal Plants for Anti-neurodegenerative diseases in West Africa, Journal of Ethnopharmacology, 285, 2022, 114468, https://doi.org/10.1016/j.jep.2021.114468.
[3] C. Jansen, J.D. Baker, E. Kodaira, L. Ang, A.J. Bacani, J.T. Aldan, L.M.N. Shimoda, M. Salameh, A.L. Small-Howard, A.J. Stokes, H. Turner, C.N. Adra, Medicine in motion: Opportunities, challenges and data analytics-based solutions for traditional medicine integration into western medical practice, Journal of Ethnopharmacology, Volume 267, 2021, https://doi.org/10.1016/j.jep.2020.113477.
[4] Şenay Kafkas, Robert Hoehndorf, Ontology based text mining of gene-phenotype associations: application to candidate gene prediction, Database, Volume 2019, 2019, baz019, https://doi.org/10.1093/database/baz019n

## Reporting:
- notes on: [Gdoc]()
- BioHackRxiv manuscript: [BioHackrxiv-metabolinet](https://github.com/bio-ontology-research-group/metabolitenet/tree/master/biohackrxiv)

## Theme:

data and text mining (with focus on Middle East)

## Team leader:
 * Name: Núria Queralt Rosinach
 * Contact: nqueralt.r@gmail.com
 
## Submission number:

29
