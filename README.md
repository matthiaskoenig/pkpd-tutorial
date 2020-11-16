# Tutorial on building a PK/PD model
**Matthias König**

## 1. Data curation
A first step for model building is data curation. The timecourse and pharmacokinetics data are used for model fitting (calibration) and for validation of model prediction.

Typical simulations with the curated datasets are
* dose-dependency of pharmacokinetic parameters
* effect of application routes (oral vs intravenous)
* apply the model to new questions, e.g., hepatic impairment / renal impairment.

For the different conditions respective datasets are required.

For details about the curation process see
https://github.com/matthiaskoenig/pkdb_data/blob/develop/CURATION.md

## 2. Model building (SBML)

All models are encoded in Systems Biology Markup Language (**SBML**). Information related to SBML is available from the SBML homepage (http://sbml.org/Main_Page) and the following introductionary publications:
=======
This document provides a high level overview into resources and tools used to build physiological-based pharmacokinetics/pharmacodynamcis (PK/PD) models in the [König group](https://livermetabolism.com).

## Introduction into Python
* [Introduction into Python](./python.md)
* [Introduction into git and github](./git.md)
* [Data curation](./data_curation.md)
* [Model building](./model_building.md)
* [Model visualization](./model_building.md)
* [Parameter fitting](./parameter_fitting.md)
* [Sensitivity analysis](./sensitivity_analysis.md)

&copy; 2017-2020 Jan Grzegorzewski & Matthias König; https://livermetabolism.com.
 


