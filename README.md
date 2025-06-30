# CG_backmapping

trjconv 5.0 or newer is recommended to convert Gromacs files (xtc, trr, gro) to PDB files. Please make sure different protein chains/segments have different chain IDs, and the lipids have correct residue names in the PDB file.

# check https://manual.gromacs.org/current/onlinehelp/gmx-trjconv.htm
gmx trjconv -s md.tpr -f md.gro -o backmapping.pdb -n index.ndx 
