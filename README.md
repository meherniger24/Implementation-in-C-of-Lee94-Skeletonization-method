# Full Implementation of Lee94 skeletonization in C++ 
This repository provides a complete implementation of the Lee et al. (1994) 3D sequential thinning / medial axis skeletonization algorithm written entirely in C++.
The method is widely used in FIJI/ImageJ, scikit-image, and other biomedical image processing tools for extracting centerlines, medial surfaces, and 3D skeletons from volumetric data.

This implementation reproduces the full logic of the original paper—including topology-preserving deletion rules, Euler look-up tables, endpoint checks, and 26-connectivity analysis—while offering a clear and modular C++ structure.
