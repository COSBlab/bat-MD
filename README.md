# bat-MD
Repository of the data needed to reproduce the Molecular Dynamics simulations of the human RBD in complex with the human ACE2 (hRBD-hACE2), the bat-236 RBD in complex with the human ACE2 (bRBD-hACE2), and the bat-236 RBD in complex with the bat ACE2 (bRBD-bACE2). Simulations have been performed using GROMACS 2020.4.

The repository is organized in the following directories:

* 0-TOPO: topology files in GROMACS format
* 1-EQUIL: protocol to perform equilibration of the system. Detailed instructions are contained in do_equilibration.sh.
* 2-PRODUCTION: protocol to perform production simulation. Detailed instructions are contained in do_production.sh.
* 3-ANALYSIS: Scripts and codes to perform analysis of the simulations.
