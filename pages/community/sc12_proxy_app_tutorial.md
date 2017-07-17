---
title: SC12 Proxy App Tutorial
folder: community
permalink: sc12_proxy_app_tutorial.html
---

This page has resources specific to the SC’12 Tutorial on Proxy Applications.

## Downloads

### Featured Proxy Apps:

*   [CoMD](https://github.com/exmatex/CoMD): Molecular Dynamics Proxy Applications Suite. Download a [zip](https://github.com/exmatex/CoMD/archive/master.zip) file or learn about how to get a read-only clone on the [CoMD github site](https://github.com/exmatex/CoMD).
*   [LULESH](https://computation.llnl.gov/casc/ShockHydro): Shock Hydrodynamics Proxy Application. Download the serial distribution [here](https://computation.llnl.gov/casc/ShockHydro/LULESH-files/LULESH-1.0.1.tgz). A [hybrid (MPI/OpenMP)](http://www.mantevo.org/downloads/luleshMPI_OMP.cc) version of the source code is also available.
*   [MiniFE](packages.html): Implicit Finite Element Proxy Application. Download the [reference](http://www.mantevo.org/downloads/miniFE_ref-1.2.tar.gz) version or the [full (reference + OpenMP)](http://www.mantevo.org/downloads/miniFE-1.2.tar.gz) version.
*   [MiniGhost](packages.html): Finite-Difference Proxy Application. Download the [reference](http://www.mantevo.org/downloads/miniGhost_ref-0.1.tar.gz) version or the [full](http://www.mantevo.org/downloads/miniGhost-0.1.tar.gz) version.

### Virtual Machine:

A VirtualBox virtual machine preloaded with the proxy apps featured at the tutorial is available. Not all versions of the featured proxy apps are available in the virtual machine. Instructions for setting up the virtual machine are below.

1.  Download and install VirtualBox from [virtualbox.org](https://www.virtualbox.org/wiki/Downloads).
2.  Download the Tiny Core Linux 4.7 virtual machine from [here](http://www.mantevo.org/downloads/ProxyAppTutorialSC12.ova) or [here](https://software.sandia.gov/mantevo/ProxyAppTutorialSC12.ova). Do not allow the file to be downloaded as a .tar file instead of a .ova file.
3.  Open VirtualBox, and use <tt>File->Import Appliance</tt> to import the virtual machine. If your machine has only one core, or if an error occurs at start up, reduce the value of <tt>CPU</tt> to 1\. If your machine has less than 3 GB ram, reduce the value of <tt>RAM</tt> to no more than half of the ram on the machine. These changes can be made during the import process, or after importing by clicking on <tt>Settings</tt>, then <tt>System</tt>.
4.  <tt>Start</tt> the virtual machine.
5.  In the <tt>Machine</tt> menu on the window for the virtual machine, select <tt>Disable Mouse Integration</tt>. (You will need to capture the mouse by clicking in the virtual machine screen area. When you want to leave the virutal screen, you will need to press <tt>right Ctrl</tt> for Linux or Windows, or <tt>left command</tt> on Mac.)
6.  Click on the terminal icon, second from the left, in the bottom menu and review the <tt>README.txt</tt> file to get started.