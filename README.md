# xPK2x
Software to calculate elastic constants up to the fourth order of solid materials from first principles

=============================
SOFTWARE
=============================

 xPK2x encompasses three simple Fortran codes 
 and one Bash script that can be used to calculate  
 elastic constants up to the fourth order of a 
 solid material described by using a periodic 
 density functional theory (DFT) approach. 
 At present, xPK2x is designed to work in conjunction 
 with the Quantum Espresso software package for 
 electronic structure calculations. 

=============================
REQUIREMENTS
=============================

 A Fortran compiler, BLAS and LAPACK libraries.

=============================
INSTALLATION AND USE
=============================

Enter the directory ./src, edit the Makefile to 
provide name of the Fortran compiler and path of 
the BLAS and LAPACK libraries, and type 'make all'.

We refer to the pdf file 'user_guide.pdf' in 
the directory ./docs for a full description of 
the software xPK2x and how to use it. In this 
document, several examples are also discussed 
in detail.

=============================
FILES AND DIRECTORY STRUCTURE
=============================

Main files and directories provided in this repository 
are shown below.

 .
 ├── AUTHORS.rst
 ├── LICENSE
 ├── README
 ├── docs
 │   ├── user_guide.pdf
 │   └── user_guide.tex
 ├── examples
 │   ├── Al
 │   ├── C
 │   ├── Mg
 │   ├── free
 │   └── pps
 └── src
     ├── dft.str_ten.sh
     ├── Makefile
     ├── pk2ecs.f90
     ├── pk2open.f90
     ├── str2pk.f90
     ├── strvec.C123
     ├── strvec.cub
     └── strvec.hex
