# Scattering_code
A Mathematica notebook to estimate scattering from molecular dynamics simulation
pdbfiles contain pdb files of 100 frames of P3HT (12 monomer) simulated at 600K
overall.nb is a mathematica notebook which reads the pdb files and estimate the overall scattering.
intrachain.nb is a mathematica notebook which reads the pdb files and estimate average scattering from individual molecule. To obtain interchain scattering, number of molecule (64) times the intrachain scattering need to be subtracted from the overall scattering.
