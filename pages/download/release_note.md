---
title: Release Notes
folder: download
permalink: release_notes.html
---

## Mantevo Suite Release 3.0

November 2014

The third major release of the Mantevo suite of mini applications and mini drivers is available for download.

Mantevo packages are small programs that embody one or more performance impacting elements of large-scale production applications. A number of Mantevo packages have already been successfully used as part of the “co-design” of new computer systems and applications during this time of rapid transition to scalable multicore and accelerator based computer systems.

Mantevo Suite Release 3.0 includes fifteen packages, including thirteen Miniapplications: CloverLeaf, CloverLeaf3D*, CoMD, HPCCG, MiniAero*, MiniAMR*, MiniFE, MiniGhost, MiniMD, MiniSMAC2D, MiniXyce, Pathfinder*, and TeaLeaf*, and two Minidrivers: CleverLeaf and EpetraBenchmarkTest.

*denotes first release of the miniapp

### Proxy Application Release Notes

#### Cleverleaf

Reference version 2.0:

1.  Added custom memory-aligned data types.
2.  Refactored sources into folders for geometry, hydro, and patch data.
3.  OpenMP directives are now present in all coarsen/refine routines.
4.  Fixed a bug when refining flux values.

#### CloverLeaf

Reference version 1.1: Various performance optimisations and improvements, specifically around the OpenMP support.

#### CloverLeaf3D

Reference version 1.0: 3D version of the CloverLeaf mini-app.

#### miniAMR

Reference version 1.0: 3D stencil calculation with Adaptive Mesh Refinement (AMR).

#### miniFE

Reference version 2.0.1: Some small bug fixes related to using OpenMP on the Cray XC30.

#### miniSMAC2D

Reference version 2.0:

1.  Added OpenMP directives.
2.  Batch scripts, appropriate Makefiles, and boundary condition files have been generated and are included.
3.  Two larger test cases added.
4.  Output file formatted for plotting with tools such as Plot3D or TECPLOT.

#### PathFinder

Reference version 1.0: Signature search.

#### TeaLeaf

Reference version 1.0: Heat conduction code utilising implicit solvers (Conjugate Gradient and Chebyshev) on a 5-point stencil.

For more information, or to download these packages, visit the following links.

Mantevo website: [Mantevo.org](http://mantevo.org)  
Mantevo Suite 3.0 [Download page](download.html)

## Mantevo Suite Release 2.0

November 2013

The second major release of the Mantevo suite of mini applications and mini drivers is available for download.

Mantevo packages are small programs that embody one or more performance impacting elements of large-scale production applications. A number of Mantevo packages have already been successfully used as part of the “co-design” of new computer systems and applications during this time of rapid transition to scalable multicore and accelerator based computer systems.

Mantevo Suite Release 2.0 includes ten packages, including eight Miniapplications: CloverLeaf, CoMD, HPCCG, MiniFE, MiniGhost, MiniMD, MiniSMAC2D, and MiniXyce, and two Minidrivers: CleverLeaf and EpetraBenchmarkTest.

For more information, or to download these packages, visit the following links.

Mantevo website: [Mantevo.org](http://mantevo.org)  
Mantevo Suite 2.0 [Download page](download.html)

## Mantevo Suite Release 1.0

November 2012

The first official release of the Mantevo suite of mini applications and mini drivers is available for download.

Mantevo packages are small programs that embody one or more performance impacting elements of large-scale production applications. A number of Mantevo packages have already been successfully used as part of the “co-design” of new computer systems and applications during this time of rapid transition to scalable multicore and accelerator based computer systems.

Mantevo Suite Release 1.0 includes eight packages, including seven Miniapplications: CloverLeaf, CoMD, HPCCG, MiniFE, MiniGhost, MiniMD, and MiniXyce, and one Minidriver: EpetraBenchmarkTest.

For more information, or to download these packages, visit the following links.

Mantevo website: [Mantevo.org](http://mantevo.org)  
Mantevo Suite 1.0 [Download page](previous_releases)