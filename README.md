# biotea-ontololgy
An ontology to support the RDFization of scientific documents in the Biotea project. Specifically, it supports group-based distribution and semantic similarity.

## Background

### Semantic similarity 

Similarity between a query document and a related document taking into account semantic annotations identified in the text. A semantic annotation is a word or set of words associated to an ontological term. The similarity can be restricted to some particular groups defined in a model.

### Group-based distribution

Distribution of all the terms in a document according to a model describing a set of groups. Every group gets a score [0.0, 1.0] and the summation of all scores is 1.0.

### Model
Both group-based distribution and semantic similarty refers to a model of semantic groups such as UMLS or Biolinks. Biolinks is a customization of UMLS semantic groups aiming for more granular groups. The groups consider in Biolinks are: ACTI (Activities & Behaviors), ANAT (Anatomy), CHEM (Chemical entities), CONC (Concepts & Ideas), DEVI (Devices), DISO (Disorders), DRUG (Drugs), GENE (Genes & Molecular Sequences), GEOG (Geographic Areas), GNPT (DNA & Protein molecules), OBJC (Objects), OBSV (Physiology attributes & processes), OCCU (Occupations), ORGA (Organizations), PEOP (People and population groups), PHEN (Phenomena), PHYS (Physiological functions), PROC (Procedures), SYMP (Disorder symptoms) and TAXA (Taxonomic terms).

## Ontology at a glance

Semantic similarity model
![](similarity model.png)

Group-based distribution model
![](topic distribution model.png)


## Classes


## Object properties

## Data properties
