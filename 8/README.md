# Project 8

## Title:

Open MENA Microbiome Project

## Description:

### Problem 
Microorganisms inhabiting our bodies (also called
“microbiome") play a critical role in our health by helping the
immune system, controlling digestion, and even affecting mental
health. Imbalances and certain perturbations in the microbiome may be
the reason for severe health disorders including diabetes,
cardiovascular diseases, overweight, cancer, and many
others. According to Richard J. Abdill et al. [1], microbiome research
is underrepresented in the MENA region despite this critical role in
human health. A look at the Human Gut Microbiome Atlas confirms this,
as the MENA region is not represented. Yet MENA is a region with a
distinctive environment and diet which are usually significant markers
for microbiome compositions and related phenotypes.

### Solution 
Our goal is to build an interactive microbial map of
the MENA region and associated diseases.  Such an association map will
provide an overview of microbial composition in this region. Also, it
will help the further investigation of host-microbiome interactions
and associated diseases specific to the MENA population.

### Data
Several related open microbiome studies have been described
by K. J. Alzahrani [2], M. Yasir et al. [3], and S. Radwan et
al. [4]. In our project, we will use BacDive which is the world's
largest database for standardized bacterial information. In addition,
we would like to use PathoPhenoDB which is a database of human
pathogens and associated diseases.

### Methods
We will access the microbiome information through
publically available APIs and using a query language SPARQL which is a
semantic query language for databases. For unannotated samples, we
will predict the taxonomy by taking a baseline machine learning
algorithm from the open-source microbiome bioinformatics platform
QIIME2.  The baseline algorithm is trained on the data from Silva
database, we can improve its performance by fitting additional data
from the MENA region and tuning model hyperparameters. The proposed
interactive visualization map will contain information about bacterial
species and associated phenotype information including diseases.

### Future work
There are various types of microbiome data that can
expand our solution, such as amplicon sequencing, single-cell, and
metagenomics data. Moreover, there are different types of OMICs data,
e.g., metabolomics, that are crucial for studying microbial
taxa-disease associations. During the five days of the hackathon, we
will make the first step to creating a bigger ontology of microbiome
studies in the MENA region. This step will potentially lead to a
deeper investigation of the currently underestimated role of the
microbiome in the MENA population health.


### References:
1. Abdill, R.J., Adamowicz, E.M. and Blekhman, R., 2022. Public human
   microbiome data are dominated by highly developed countries. PLoS
   biology, 20(2), p.e3001536.
2. Alzahrani, K.J., 2021. Microbiome Studies from Saudi Arabia over
   the Last 10 Years: Achievements, Gaps, and Future
   Directions. Microorganisms, 9(10), p.2021.
3. Yasir, M., Angelakis, E., Bibi, F., Azhar, E.I., Bachar, D.,
   Lagier, J.C., Gaborit, B., Hassan, A.M., Jiman-Fatani, A.A.,
   Alshali, K.Z. and Robert, C., 2015. Comparison of the gut
   microbiota of people in France and Saudi Arabia. Nutrition &
   diabetes, 5(4), pp.e153-e153.
4. Radwan, S., Gilfillan, D., Eklund, B., Radwan, H.M., El Menofy,
   N.G., Lee, J., Kapuscinski, M. and Abdo, Z., 2020. A comparative
   study of the gut microbiome in Egyptian patients with Type I and
   Type II diabetes. PloS one, 15(9), p.e0238764.
   
## Theme:

interoperable resources, databases, ontologies (with focus on Middle
East)

## Team leader:
	
 * Name: Oleg Vlasovets
 * Contact: oleg.vlasovetc@helmholtz-muenchen.de
 
## Submission number:

30
