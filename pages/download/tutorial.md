---
title: Tutorial
folder: download
permalink: tutorial.html
---

### Virtual Machine:

A VirtualBox virtual machine preloaded with the proxy apps featured at the SC12 Proxy App Tutorial is available. Not all versions of the featured proxy apps are available in the virtual machine. Instructions for setting up the virtual machine are below.

1.  Download and install VirtualBox from [virtualbox.org](https://www.virtualbox.org/wiki/Downloads).
2.  Download the Tiny Core Linux 4.7 virtual machine from [here](http://mantevo.org/downloads/ProxyAppTutorialSC12.ova) or [here](https://software.sandia.gov/mantevo/ProxyAppTutorialSC12.ova). Do not allow the file to be downloaded as a .tar file instead of a .ova file.
3.  Open VirtualBox, and use File->Import Appliance to import the virtual machine. If your machine has only one core, or if an error occurs at start up, reduce the value of CPU to 1\. If your machine has less than 3 GB ram, reduce the value of RAM to no more than half of the ram on the machine. These changes can be made during the import process, or after importing by clicking on Settings, then System.
4.  Start the virtual machine.
5.  In the Machine menu on the window for the virtual machine, select Disable Mouse Integration. (You will need to capture the mouse by clicking in the virtual machine screen area. When you want to leave the virutal screen, you will need to pressright Ctrl for Linux or Windows, or left command on Mac.)
6.  Click on the terminal icon, second from the left, in the bottom menu and review the README.txt file to get started.