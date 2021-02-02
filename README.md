## Introduction
The repository contains the work done on computation of Couette-Poiseuille flow with a mixing-length model of turbulence. This work
was done as of part of turbulence practices - <code>Individual Research Project</code> at École centrale de Lille, France as a part of
Masters program in Turbulence. The project was a supervised of Dr. Jean-Philippe LAVAL.

<code>Objective:</code> 
To write a simple program for a turbulent model for a simplified case and compare the results with the <code>theoritical solutions</code> in                         the <code>laminar case</code> and with the <code>experimental</code> results in <code>turbulent case</code>. Several parameters such as grid stretching, number of grid points near the walls are investegated.

## Prerequisites


- Go to build directory : 
    cd build 
    rm -f CMakeCache.txt

- Create Makefile with one of these command choosing compiler (gfortran, ifort, ...) 
  and build type (Debug, Release, ...).
  
  - To compile with compiler Release flags only  
  `FC=gfortran cmake -D PLATFROM_NAME=lmlm6-75 CMAKE_BUILD_TYPE=Debug  ..`
  `FC=mpif90.openmpi cmake -D PLATFROM_NAME=lmlm6-75 CMAKE_BUILD_TYPE=Debug  ..`



















