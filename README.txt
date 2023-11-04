The following files are provided:

(1) Sample input LAMMPS data files for different photoacid generator (PAG) chemistries 
	in poly(4-hydroxy styrene) and poly(tert-butyl methacrylate) homopolymers and alternating copolymers.

(2) Modified LAMMPS source scripts are provided to carry out Hamiltonian Replica Exchange.
    Please check the comments to see where the original scripts are edited. Following files should be used while compiling the LAMMPS executable: 
    fix.h, fix_spring.cpp, fix_spring.h, temper_npt.cpp,temper_npt.h

(3) LAMMPS scripts to run high PAG concentration simulations. 
	Sequence for running the LAMMPS scripts for high PAG simulations: in.adapt->in.startljcoul->in.final

All simulations were performed using the LAMMPS 29th September 2021 version. More details on the Metropolis acceptance, OPLS-AA forcefield parameters, and simulation
protocols can be found in the manuscript titled: Atomistic modeling approach for predicting association of photoacid generators in extreme ultraviolet polymeric 
photoresists (https://doi.org/10.1021/acs.chemmater.3c01750)
