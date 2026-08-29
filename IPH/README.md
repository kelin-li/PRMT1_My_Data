```
# IPH Cosolvent MD Simulations

This directory contains the input files and analysis results for PRMT1 with IPH as a cosolvent probe.

## Files
- `SAM_IPH.cut10.wat.prmtop`: Topology file (AMBER format)
- `SAM_IPH.cut10.wat.inpcrds`: Initial coordinates
- `SAM_IPH.equil.norests.rst`: Equilibrated structure
- `md1.in`: Production MD input parameters

## Replicates
Three independent MD replicates (500 ns each) were performed by assigning different initial random velocities. The topology and coordinate files are identical across replicates and are provided once here.

## Analysis Results
The `analysis/` subdirectory contains trajectory analysis data from the first replicate (run1), including:
- RMSD and RMSF profiles
- Representative snapshots at different time points
- Other structural analyses

For replicates 2 and 3, the same static files were used with different random seeds; their full trajectories are available upon reasonable request.
```