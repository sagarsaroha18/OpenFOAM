# OpenFOAM
This directory contains code for ShihQuadraticKE turbulence model.

# Installation
Please ensure that OpenFOAM  is installed and compiled as a pre-requisite.
This solver is tested and validated to work for the OpenFOAM (version 5).

0. Download the ShihQuadraticKE.C and ShihQuadraticKE.H files in the OpenFOAM folder.
1. Go to the folder and run the following command in the terminal launched from the directory containing the above files.
$ wclean .all

2. To compile the turbulence model, run the following command in the terminal
$ wmake 
