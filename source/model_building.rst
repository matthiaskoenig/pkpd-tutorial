Model building
==============

All models are encoded in Systems Biology Markup Language (**SBML**). Most materials related to SBML are available from the homepage http://sbml.org/Main_Page.

A high level overview is given in the following documents:

> Hucka, M., Finney, A., Sauro, H.M., Bolouri, H., Doyle, J.C., Kitano, H., Arkin, A.P., Bornstein, B.J., Bray, D., Cornish-Bowden, A. and Cuellar, A.A., 2003. The systems biology markup language (SBML): a medium for representation and exchange of biochemical network models. Bioinformatics, 19(4), pp.524-531.

[./literature/SBML_L2_paper.pdf](resources/SBML_L2_paper.pdf)

> SBML Level 3 publication

[./literature/SBML_L3_paper_final_revisions.pdf](resources/SBML_L3_paper_final_revisions.pdf)


A detailed specification of SBML is provided here:
> SBML specification document

[./literature/sbml-level-3-version-2-release-2-core.pdf](resources/sbml-level-3-version-2-release-2-core.pdf)

We create SBML models using the library
https://github.com/matthiaskoenig/sbmlutils  
https://sbmlutils.readthedocs.io/en/stable/  

SBML models are simulated using `sbmlsim`
https://github.com/matthiaskoenig/sbmlsim  

It provides an abstraction layer around `roadrunner`
https://github.com/sys-bio/roadrunner/
http://libroadrunner.org/

publication in [./literature/libroadrunner.pdf](resources/libroadrunner.pdf)

## Model information
The model creation code creates SBML files and SBML reports (HTML) which provide an overview over model content.
The reports are very helpful for getting SBML identifiers and respective units.

## Model building:
- how to setup pycharm
- how to install pkdb_models via pip