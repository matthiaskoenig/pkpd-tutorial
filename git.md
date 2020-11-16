# Git and github
All data and code is managed using a the **version control system** git with using github as a platform. A great introduction about the advantages of git and github in the bioinformatics can be found in [Perez-Riverol2019](./literature/git/Perez-Riverol2019.pdf).  

Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later. It allows multiple people to work cooperatively to work on a project. For a nice introduction read [getting started - about version control](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) and [getting started - what is git](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F).

An overview over online resources can be found at https://try.github.io/. We recommend to do the following short online course giving an overview in git commands such as `branch`, `add`, `commit`, `merge`: Online course: https://learngitbranching.js.org/ 

A cheat sheet of the most important git commands can be found here: https://training.github.com/downloads/github-git-cheat-sheet.pdf

## Most important git commands
Only a handful commands are used to work with git. 
### Initial setup
After git installation you should first setup your environment via
```
git config --global user.name "[name]" 
```
Sets the name you want attached to your commit transactions
```
git config --global user.email "[email address]"
```
Sets the email you want attached to your commit transactions

```
git config --global color.ui auto
```
Enables helpful colorization of command line output










## References
* git book - Getting started - About version control, https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control
* git book - Getting started - What is git?, https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F
* resources to learn git, https://try.github.io/
* online course git; https://learngitbranching.js.org/ 
* Perez-Riverol Y, Gatto L, Wang R, Sachsenberg T, Uszkoreit J, Leprevost Fda V, Fufezan C, Ternent T, Eglen SJ, Katz DS, Pollard TJ, Konovalov A, Flight RM, Blin K, Vizcaíno JA. Ten Simple Rules for Taking Advantage of Git and GitHub. PLoS Comput Biol. 2016 Jul 14;12(7):e1004947. doi: 10.1371/journal.pcbi.1004947. Erratum in: PLoS Comput Biol. 2019 Jun 14;15(6):e1007142. PMID: 27415786; PMCID: PMC4945047. [PDF](./literature/git/Perez-Riverol2019.pdf)
