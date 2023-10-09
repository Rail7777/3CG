# 3CG
Center-Corner Cubes Growing (3CG) algorithm for determining the representative elementary volume (REV) of pore space in a binarized image stack.

3CG operates by analyzing porosity within cubes growing from each of the eight corners and a central region of a 3D binarized image. It systematically computes porosity for various cube sizes, determining the average porosity and standard deviation for each extent.

Install Jupyter Notebook or Python 3.9.16 for work.

Use TIF or PNG format for the image stack. The pores should be white (1) on binarized images.

Cite the work: _**Kadyrov, R.I., 2023. Multiple cubes growth algorithms for simple REV determination on 3D binary images. Scientific Visualization.**_
