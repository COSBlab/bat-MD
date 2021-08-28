# bat-MD
Repository of the data needed to reproduce the Molecular Dynamics simulations of 3 different RBD-ACE2 complexes.
 All simulations have been performed using GROMACS 2020.4. The repository is organized in the following directories:

* *hRBD-hACE2*: data related to the simulations of the human-RBD/human-ACE2 complex;
* *b103RBD-hACE2*: data related to the simulations of the BANAL-103-RBD/human-ACE2 complex;
* *b236RBD-hACE2*: data related to the simulations of the BANAL-236-RBD/human-ACE2 complex.

Inside each of these directories, you will find 3 subdirectories named *RUN.X*, which contain:
* *0-TOPO*: topology files in GROMACS format;
* *1-EQUIL*: run energy minimization and equilibration using the protocol in *do_emin_equil.sh*;
* *2-PRODUCTION*: run production using the protocol in *do_production.sh*;
