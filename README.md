This Jupyter notebook is a Python script that implements a coarsening scheme for scalar fields. While it is currently applied to a turbulent viscosity field, the methodology is general and can be extended to any field.

The core idea is:
Given the coordinates of a fine mesh and its corresponding field values, along with the coordinates of a coarse mesh, the script outputs the coarsened field on the coarse mesh.

Additionally, the script computes error metrics to quantify the accuracy of the coarsening scheme.
It is a script tailored to OpenFOAM files but can be generalized also to other input files.
