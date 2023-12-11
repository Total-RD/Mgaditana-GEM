# Mgaditana-GEM: Genome-scale metabolic model of _Microchloropsis gaditana_

### Description

This repository contains the genome-scale metabolic model (GEM) of _Microchloropsis gaditana_, named **iMgadit23**.

### Authors/Contributors

Clémence Dupont-Thibert<sup>1,2</sup>, Sónia Carneiro<sup>3</sup>, Bruno Pereira<sup>3</sup>, Rafael Carreira<sup>3</sup>, Paulo Vilaça<sup>3</sup>, Giovanni Finazzi<sup>1</sup>, Séverine Collin<sup>2</sup>, Eric Maréchal<sup>1</sup>, Elodie Billey<sup>2</sup>, Gilles Curien<sup>1</sup>, Maxime Durot<sup>2</sup>, Juliette Jouhet<sup>1</sup>

1 - Université Grenoble Alpes, CNRS, CEA, INRAE, Interdisciplinary Research Institute of Grenoble, IRIG-Laboratoire de Physiologie Cellulaire et Végétale, 17 Avenue des Martyrs, 38000 Grenoble, France  
2 - TotalEnergies, OneTech, Centre de Recherche de Solaize CRES, Chemin du Canal, 69360 Solaize, France  
3 - SilicoLife Lda. Rua do Canastreiro, 15 4715-387 Braga, Portugal  

### Keywords

**Utilisation:** experimental data reconstruction; multi-omics integrative analysis; _in silico_ strain design; model template  
**Field:** metabolic-network reconstruction  
**Type of model:** reconstruction; curated  
**Model publication:** [https://doi.org/10.1101/2023.12.06.570374](https://doi.org/10.1101/2023.12.06.570374)  
**Omic source:** [genomics](https://www.ncbi.nlm.nih.gov/datasets/genome/GCA_000569095.1/); [lipidomics](https://academic.oup.com/plphys/article/185/3/815/6094630?login=false)  
**Taxonomic name:** _Microchloropsis gaditana_ (formerly _Nannochloropsis gaditana_)  
**Taxonomy ID:** [taxonomy:72520](https://identifiers.org/taxonomy:72520)  
**Genome ID:** [insdc.gca:GCA_000569095.1](https://identifiers.org/insdc.gca/GCA_000569095.1)  
**Metabolic system:** general metabolism  
**Strain:** B-31  
**Biomass Objective Functions:** iMgadit23 contains two independent BOFs, representing respectively biomass composition of WT526 and [MgACSBG#31](https://academic.oup.com/plphys/article/185/3/815/6094630?login=false) strains  
**Condition:** photo-autotrophy, photon uptake upper bound constrained to -23 mmol.gDW<sup>-1</sup>.h<sup>-1</sup>

### Model Overview

| Taxonomy | Version | Reactions | Metabolites | Genes |
| ------------- |:-------------:|:-------------:|:-------------:|:-----:|
|  _Microchloropsis gaditana_ | 1.0.0 | 2330  | 1977 | 889 |


### Installation

If you want to use the model, any software that accepts SBML Level 3 Version 1 formatted model files will work. We recommend the following as they are well-maintained and used by most researchers in the constraint-based metabolic modeling community:
* MATLAB
  * [COBRA Toolbox](https://github.com/opencobra/cobratoolbox) and [RAVEN Toolbox](https://github.com/SysBioChalmers/RAVEN)
* Python
  * [cobrapy](https://github.com/opencobra/cobrapy)

The [model](https://github.com/Total-RD/Mgaditana-GEM/model) and its [2D-Pathway Map](https://github.com/Total-RD/Mgaditana-GEM/map) are also provided in JSON format compatible with [Escher](https://escher.github.io/#/) and [Escher-FBA](https://sbrg.github.io/escher-fba/#/).