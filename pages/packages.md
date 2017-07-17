---
title: Packages
permalink: packages.html
---

*   ***CloverLeaf:** [CloverLeaf](http://uk-mac.github.io/CloverLeaf/) is a miniapp that solves the compressible Euler equations on a Cartesian grid, using an explicit, second-order accurate method.
*   ***CloverLeaf3D**: [CloverLeaf3D](http://uk-mac.github.io/CloverLeaf3D/) is <span class="Apple-style-span" style="color: #000000;"><span class="Apple-style-span" style="color: #373737;">3D version of the CloverLeaf mini-app.</span></span><span style="color: #373737;"></span>
*   ***CoMD:** A simple proxy for the computations in a typical molecular dynamics application. The reference implementation mimics that of SPaSM. In addition, we provide an OpenCL implementation which allows testing on multicore and GPU architectures, with both array-of-structures and structure-of-arrays data layouts. More information can be found at [https://github.com/exmatex/CoMD](https://github.com/exmatex/CoMD).
*   <span style="color: #373737;">***MiniAero**: MiniAero is a mini-application for the evaulation of programming models and hardware for next generation platforms. MiniAero is an explicit (using RK4) unstructured finite volume code that solves the compressible Navier-Stokes equations. Both inviscid and viscous terms are included. The viscous terms can be optionally included or excluded.</span>
*   ***MiniAMR**: <span class="Apple-style-span" style="color: #000000;"><span class="Apple-style-span" style="color: #373737;">3D stencil calculation with Adaptive Mesh Refinement (AMR).</span></span>
*   ***MiniFE:** MiniFE is an proxy application for unstructured implicit finite element codes. It is similar to HPCCG and pHPCCG but provides a much more complete vertical covering of the steps in this class of applications. MiniFE also provides support for computation on multicore nodes, including pthreads and Intel Threading Building Blocks (TBB) for homogeneous multicore and CUDA for GPUs. Like HPCCG and pHPCCG, MiniFE is intended to be the “best approximation to an unstructured implicit finite element or finite volume application, but in 8000 lines or fewer.”
*   ***HPCCG:** Intended to be the “best approximation to an unstructured implicit finite element or finite volume application in 800 lines or fewer.”
*   **pHPCCG:** A parametrized version of HPCCG that supports use of different scalar and integer data types, as well as different sparse matrix data structures.
*   ***MiniMD:** A simple proxy for the force computations in a typical molecular dynamics applications. The algorithms and implementation used closely mimics these same operations as performed in LAMMPS.
*   ***MiniGhost:** A Finite Difference proxy application which implements a difference stencil across a homogenous three dimensional domain.
*   ***MiniSMAC2D:** Solves the finite-differenced 2D incompressible Navier-Stokes equations with Spalart-Allmaras one-equation turbulence model on a structured body conforming grid. The grid is partitioned into subgrids load balanced for the number of MPI ranks requested by the user. Subgrids overlap one grid point for point-to-point boundary communication. MiniSMAC2D currently features implicit line and symmetric Gauss-Seidel relaxation algorithms. As a test case, input files are included for a C-grid around a NACA 4412 airfoil at angle of attack.
*   **miniTri**: [miniTri](https://github.com/Mantevo/miniTri) is a triangle based data analytics miniapp. It is a proxy for an important class of triangle based data analytics applications. miniTri attempts to be more application relevant than standard data analytics benchmarks such as Graph 500.
*   **phdMesh:** Parallel heterogeneous dynamic mesh application. Exhibit the performance characteristics of the contact search operations in an explicit finite element application.
*   ***MiniXyce:** A portable proxy of some of the key capabilities in the electrical modeling Xyce.
*   ***Pathfinder**: Signature search.
*   ***TeaLeaf**: [TeaLeaf](http://uk-mac.github.io/TeaLeaf/) is a mini-app that solves the linear heat conduction equation on a spatially decomposed regularly grid using a 5 point stencil with implicit solvers.

*   **Minidrivers:**
    *   **Beam:** Wraps the Trilinos packages for forming element stiffness matrices (the Intrepid package), assembling them (the FEI package) and solving the resulting linear system (using AztecOO, ML, Ifpack and Epetra packages).
    *   ***CleverLeaf:** CleverLeaf is a minidriver that uses the hydrodynamics kernels of CloverLeaf in combination with the SAMRAI library to solve the compressible Euler equations on a two-dimensional adaptive mesh.
    *   ***Epetra Kernels Benchmark:** Driver that executes key performance-impacting Epetra kernels for sparse matrix-vector, sparse matrix-multivector and dense kernels.*   **Motif frameworks:**
    *   **Prolego:** Driven by XML data sets that choose code fragments and weightings, Prolego can be easily configured to mimic the performance profile of a large variety of implicit and explicit unstructure finite element/volume applications.

*Denotes a miniapp/minidriver that is included in the Mantevo Suite 3.0 release.
