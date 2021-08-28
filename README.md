# Molecular Dynamics simulations of RBD-ACE2 complexes 
Repository of the data needed to reproduce the Molecular Dynamics simulations of 3 different RBD-ACE2 complexes reported in XXX.
 This repository is organized in the following directories:

* `hRBD-hACE2`: data related to the simulations of the human-RBD/human-ACE2 complex;
* `b236RBD-hACE2`: data related to the simulations of the BANAL-236-RBD/human-ACE2 complex;
* `b103RBD-hACE2`: data related to the simulations of the BANAL-103-RBD/human-ACE2 complex;
* `DATA`: various protocols, python/bash scripts and GROMACS mdp files.

Inside the first 3 directories, you will find 3 subdirectories named `RUN.X`, one for each independent run of the RBD-ACE2 complex
under study. The naming scheme is defined in Table S4 of XXX (reported at the bottom). Each `RUN.X` directory is organized as follows:
* `0-TOPO`: topology files in GROMACS format;
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
| 1 | hRBD-hACE2 | X-ray | 121/97 | 30621 | 104592 | 1000 |
| 2 | hRBD-hACE2 | X-ray | 121/97 | 30621 | 104592 | 1000 |
| 3 | hRBD-hACE2 | X-ray | 121/97 | 30621 | 104592 | 1000 |
| 4 | b236RBD-hACE2 | Homology model (top1) | 121/97 | 30502 | 104228 | 1000 |
| 5 | b236RBD-hACE2 | Homology model (top2) | 120/96 | 30140 | 103140 | 1000 |
| 6 | b236RBD-hACE2 | Homology model (top3) | 120/96 | 30090 | 102990 | 1000 |
| 7 |   b103RBD-hACE2 |	Homology model (top1) |	123/98	| 30808	| 105144 | 1000 |
| 8 |	b103RBD-hACE2 |	Homology model (top2) |	121/96	| 30135	| 103121 | 1000 |
| 9 |	b103RBD-hACE2 |	Homology model (top3) |	124/99	| 31307	| 106643 | 1000 |
