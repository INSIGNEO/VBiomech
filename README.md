# VBiomech
FE poroelastic solver

## Main references: 
 - Castro, A.P.G., Yao, J., Battisti, T., Lacroix, D., 2018. Poroelastic Modeling of Highly Hydrated Collagen Hydrogels: Experimental Results vs. Numerical Simulation With Custom and Commercial Finite Element Solvers. Front. Bioeng. Biotechnol. https://doi.org/10.3389/fbioe.2018.00142
 - Castro, A.P.G., Wilson, W., Huyghe, J.M., Ito, K., Alves, J.L., 2014. Intervertebral disc creep behavior assessment through an open source finite element solver. J. Biomech. 47, 297–301. https://doi.org/10.1016/j.jbiomech.2013.10.014

## Instructions:
1. Please make sure that you have the Intel (R) Visual Fortran Redistributables installed on your computer. If not, please install them (Folder: Libraries).

2. The program and the libraries are valid for 64-bit Windows computers. Please contact us if you need the 32-bit configuration. MacOS and Linux versions are not available.

3. Two different examples are provided:
 - Collagen hydrogel - Busby et al. (2013) 
 - Intervertebral disc - Heuer et al. (2007)

4. In each folder you will find the following input files:
 - VBIO_xyz.bcid - identification of the boundary conditions area on the FE model
 - VBIO_xyz.bio - definition of the boundary conditions to be applied on the FE model (1 file per step)
 - VBIO_xyz.unv - FE mesh file
 - VBIO_xyz_mater.dat - material properties file (1 file per material)
 - VBIO_xyz_mater.a1+ - (optional fibrillar material file)
 - VBIO_xyz_OUTdata.dat - (optional output data file)

Each file has a detailed explanation of its particularities.
Please keep the sintax as "VBIO_xyz", being xyz your preferred filename.

## Contact:
 - Andre Castro - andre.castro@sheffield.ac.uk or andre.castro@tecnico.ulisboa.pt (preferential)
 - Jose Luis Alves - jlalves@dem.uminho.pt
