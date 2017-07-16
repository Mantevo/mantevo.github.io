---
title: Applications
folder: about
permalink: applications.html
---

**Current activities:** Mantevo miniapps and minidrivers target a variety of application domains. Presently we address aspects of the following domains.

*   **Implicit unstructured partial differential equations:** Although this is a very broad area, a number of Mantevo packages address it fairly well. This is because many of these applications have a highly localized, operation-intensive phase for constructing a sparse linear system, followed by solution of the system via an iterative sparse solver. This is the most mature area for Mantevo since it is one of the most important areas for Sandia, where Mantevo started. The following miniapps and minidrivers address this domain:
    *   **MiniFE:** (Miniapp) Intended to be the best approximation to an unstructured implicit finite that includes all important computational phases.
    *   **HPCCG:** (Miniapp) Similar to MiniFE, but generates a synthetic linear system. The focus is entirely on the sparse iterative solver.
    *   **Beam:** (Minidriver) Wraps the Trilinos packages for forming element stiffness matrices (the Intrepid package), assembling them (the FEI package) and solving the resulting linear system (using AztecOO, ML, Ifpack and Epetra packages.
    *   **Epetra Kernels Benchmark:** (Minidriver) Driver that executes key performance-impacting Epetra kernels for sparse matrix-vector, sparse matrix-multivector and dense kernels.
*   **Explicit unstructured partial differential equations:** Again this is a very broad area, and very important. This domain is typified by indirect addressing, vector operations and contact detection. Mantevo has one miniapp in this area, and a few others under development.
    *   **phdMesh:** Parallel heterogeneous dynamic mesh application. Exhibits the performance characteristics of the contact search operations in an explicit finite element application.
*   **Explicit structured partial differential equations:** Again this is a very broad area, and very important. This domain is typified by highly structured stencil operations, especially communication for “halo exchange” operations.
    *   **MiniGhost:** Executes the halo exchange pattern of important structured and block-structured explicit applications.
*   **Implicit structured partial differential equations:**
    *   **MiniSMAC2D:** Solves the finite-differenced 2D incompressible Navier-Stokes equations with Spalart-Allmaras one-equation turbulence model on a structured body conforming grid. The grid is partitioned into subgrids load balanced for the number of MPI ranks requested by the user. Subgrids overlap one grid point for point-to-point boundary communication. MiniSMAC2D currently features implicit line and symmetric Gauss-Seidel relaxation algorithms. As a test case, input files are included for a C-grid around a NACA 4412 airfoil at angle of attack.
*   **Molecular Dynamics:**
    *   **MiniMD:** A light-weight molecular dynamics application containing the performance impacting code from [LAMMPS](http://lammps.sandia.gov).
    *   **CoMD:** An extensible molecular dynamics proxy applications suite featuring the Lennard-Jones potential and the Embedded Atom Method potential.
*   **Hydrodynamics:** These codes investigate the behavior and responses of materials when applied with varying levels of stress. It is common for hydrocodes to be constructed using one of two formulations – Lagrangian, in which a mesh is constructed and evolved through time, or Eulerian, where a fixed spatial region is analyzed.
    *   **CloverLeaf:** Uses a two-dimensional Eulerian formulation.
    *   **CleverLeaf:** Extends CloverLeaf’s two-dimensional Eulerian hydrodynamics for AMR meshes.
*   **Circuit Simluation:** This area is very important and quite different than PDE-based domains since the problem is inherently discrete.
    *   **MiniXyce:** Named after Sandia’s parallel circuit simulation code [Xyce](http://xyce.sandia.gov).