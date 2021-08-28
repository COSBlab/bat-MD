# Repository of scripts and GROMACS input (mdp) files
This directory contained the following items:

* `gromacs-mdps-charmm`: GROMACS input files for energy minimization, equilibration, and production;
* `count-HB.py`: python script to compute frequency of formation of inter-subunits hydrogen bonds;
* `calculate_sb.sh`: bash script to compute frequency of formation of inter-subunits salt bridges from PLUMED output;
* `get_PDB_frames.py`: convert a GROMACS xtc trajectory in individual PDB files;
* `1-do_emin_equil.sh`: protocol for energy minimization and equilibration;
* `2-do_production.sh`: protocol for production simulations;
* `3-do_analysis.sh`: protocol for the analysis of the production simulations.
