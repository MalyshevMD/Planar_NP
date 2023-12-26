This repository contains supplementary material to our article "Two-State Nanocomposite Based on Symmetric Diblock Copolymer and Planar Nanoparticles: Mesoscopic Simulation" by Maxim Malyshev, Daria Guseva and Pavel Komarov (ref., DOI:).

The archive contains input and output files (initial states and some final states) of the molecular systems discussed in the article.

For ease of use, all files are sorted into separate directories (see explanation below) and have the extension *lammpstrj.
The latter allows them to be easily opened and visualised in the freeware packages OVITO and Visual Molecular Dynamics. 

The contents
i - input files
ii - trajectory files
iii - output files 

Description of the files

Directory (i) contains the initial states of the systems, equilibrated for 1,000,000 DPD steps in athermal mode (all force parameters a_αβ = 25). These files were used as initial states to study the influence of system size (cell edge length, L, varied from 28.17σ to 51.17σ) and the degree of miscibility of blocks A and B on the resulting ordering in the system. For convenience, the file names indicate the length of the edge of the modelling cell.

Directory (ii) contains simulation trajectories for two points on the state diagram of the nanocomposite (see Figure 6 
in the article), i.e. two sets of parameters when: (a) the nanoparticle is oriented parallel to the domain plane (file out_AB40AC33BC25_(=)) and (b) the nanoparticle is oriented perpendicular to the domains of the polymer matrix (file out_AB40AC40BC40_(+)).

Directory (iii) contains the final states of the system for several sets of repulsion parameters (AB40AC25BC25 (region I), AB40AC33BC25 (region II), AB40AC40BC25 (region III), AB40AC40BC40 (region I)) from different regions of the state diagram (see Figure 6).
