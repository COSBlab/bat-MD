# Molecular Dynamics simulations of RBD/hACE2 complexes 
Repository of the data needed to reproduce the Molecular Dynamics simulations of 3 different RBD/hACE2 complexes reported in XXX.
 This repository is organized in the following directories:

* `SARS-CoV-2`: data related to the simulations of the SARS-CoV-2 RBD/hACE2 complex;
* `BANAL-236-CoV`: data related to the simulations of the BANAL-236 RBD/hACE2 complex;
* `BANAL-52-103-CoV`: data related to the simulations of the BANAL-52-103 RBD/hACE2 complex;
* `DATA`: various protocols, python/bash scripts and GROMACS mdp files.

Inside the first 3 directories, you will find 3 subdirectories, one for each independent run of the RBD/hACE2 complex
under study. The naming scheme is defined in Table S4 of XXX (reported at the bottom). Each of these directories is organized as follows:
* `0-TOPO`: initial conformation and topology files in GROMACS format;
* `1-EQUIL`: run energy minimization and equilibration here. Please refer to `README.md` for instructions;
* `2-PRODUCTION`: run production simulations here. Please refer to `README.md` for instructions; 
* `3-ANALYSIS`: analyze production simulations here. Please refer to `README.md` for instructions.

**Software requirements**
* [GROMACS 2020.4](https://www.gromacs.org)
* [PLUMED 2.7](https://www.plumed.org)
* [MDAnalysis 1.0.0](https://www.mdanalysis.org)
* [MDTraj 1.9.5](https://www.mdtraj.org/1.9.5/index.html)
* [ROSETTA 3.11](https://www.rosettacommons.org)
* [FoldX 4](http://foldxsuite.crg.eu)

**Summary of all simulations performed**

|   RUN ID	   |  Construct	| Initial model	| # K/Cl ions |	 # waters | Total # atoms | Production time [ns] |
| :------: |  :------:  |     :------:  | :------:    | :------:  | :------:      | :------:             |
| SARS-CoV-2.1 | SARS-CoV-2 RBD/hACE2 | X-ray | 121/97 | 30621 | 104592 | 1000 |
| SARS-CoV-2.2 | SARS-CoV-2 RBD/hACE2 | X-ray | 121/97 | 30621 | 104592 | 1000 |
| SARS-CoV-2.3 | SARS-CoV-2 RBD/hACE2 | X-ray | 121/97 | 30621 | 104592 | 1000 |
| BANAL-236-CoV.1 | BANAL-236 RBD/hACE2 | Homology model (top1) | 121/97 | 30502 | 104228 | 1000 |
| BANAL-236-CoV.2 | BANAL-236 RBD/hACE2 | Homology model (top2) | 120/96 | 30140 | 103140 | 1000 |
| BANAL-236-CoV.3 | BANAL-236 RBD/hACE2 | Homology model (top3) | 120/96 | 30090 | 102990 | 1000 |
| BANAL-52-103-CoV.1 | BANAL-52-103 RBD/hACE2 |	Homology model (top1) |	123/98	| 30808	| 105144 | 1000 |
| BANAL-52-103-CoV.2 | BANAL-52-103 RBD/hACE2 |	Homology model (top2) |	121/96	| 30135	| 103121 | 1000 |
| BANAL-52-103-CoV.3 | BANAL-52-103 RBD/hACE2 |	Homology model (top3) |	124/99	| 31307	| 106643 | 1000 |
