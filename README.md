# Tutorial model building
This document provides a high level overview into resources and tools used to build physiological-based pharmacokinetics models in the

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

A high level overview is given in the following documents:

> Hucka, M., Finney, A., Sauro, H.M., Bolouri, H., Doyle, J.C., Kitano, H., Arkin, A.P., Bornstein, B.J., Bray, D., Cornish-Bowden, A. and Cuellar, A.A., 2003. The systems biology markup language (SBML): a medium for representation and exchange of biochemical network models. Bioinformatics, 19(4), pp.524-531.

[./literature/SBML_L2_paper.pdf](./literature/SBML_L2_paper.pdf)

> SBML Level 3 publication

[./literature/SBML_L3_paper_final_revisions.pdf](./literature/SBML_L3_paper_final_revisions.pdf)


A detailed specification of SBML is provided here:

> SBML specification document

[./literature/sbml-level-3-version-2-release-2-core.pdf](./literature/sbml-level-3-version-2-release-2-core.pdf)

We create SBML models using the library
https://github.com/matthiaskoenig/sbmlutils  
https://sbmlutils.readthedocs.io/en/stable/  

### Model information
The model creation code creates SBML files and SBML reports (HTML) which provide an overview over model content.
The reports are very helpful for getting SBML identifiers and respective units.

## 3. Model visualization
The models can be visualized using `Cytoscape` and `cy3sbml`
- Java 11 (openjdk)
- Cytoscape >3.8.0 (https://cytoscape.org/)
- cy3sbml (see https://github.com/matthiaskoenig/cy3sbml/ for installation instructions).


## 4. Model simulation
The created SBML models can be simulated with all simulators supporting SBML, e.g. COPASI (http://copasi.org) a GUI for simulation.

We are simulating SBML models using `sbmlsim`
https://github.com/matthiaskoenig/sbmlsim  

It provides an abstraction layer around `roadrunner`
https://github.com/sys-bio/roadrunner/
http://libroadrunner.org/

publication in [./literature/libroadrunner.pdf](./literature/libroadrunner.pdf)





 


