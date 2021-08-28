# bat-MD
Repository of the data needed to reproduce the Molecular Dynamics simulations of 3 different RBD-ACE2 complexes.
 The repository is organized in the following directories:

* *hRBD-hACE2*: data related to the simulations of the human-RBD/human-ACE2 complex;
* *b103RBD-hACE2*: data related to the simulations of the BANAL-103-RBD/human-ACE2 complex;
* *b236RBD-hACE2*: data related to the simulations of the BANAL-236-RBD/human-ACE2 complex;
* *DATA*: various protocols, python/bash scripts and GROMACS mdp files.

Inside the first 3 directories, you will find 3 subdirectories named *RUN.X*, one for each independent run of the RBD-ACE2 complex
under study. The naming scheme is defined in Table S4 of XXX. Each *RUN.X* directory is organized as follows:
* *0-TOPO*: topology files in GROMACS format;
* *1-EQUIL*: run energy minimization and equilibration here. Please refer to *README.md* for instructions;
* *2-PRODUCTION*: run production simulations here. Please refer to *README.md* for instructions; 
* *3-ANALYSIS*: analyze production simulations here. Please refer to *README.md* for instructions.

**Software requirements**
* [GROMACS 2020.4](https://www.gromacs.org)
* [PLUMED 2.7](https://www.plumed.org)
* [MDAnalysis 1.0.0](https://www.mdanalysis.org)
* [MDTraj 1.9.5](https://www.mdtraj.org/1.9.5/index.html)
* [ROSETTA 3.11](https://www.rosettacommons.org)
* [FoldX 4](http://foldxsuite.crg.eu)
