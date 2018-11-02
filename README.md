This repository holds code for assignment 1 
of the Coursera course: 
Introduction to Embedded Systems Software and Development Environments

The base files were provided my the course 
and the functions filled in by me, Ankush Burman.

The purpose of this assignment was to create a Makefile and sources.mk
file from scratch to automate the build process of the provided source
and header files. The Makefile supports two target machines: HOST and MSP432.
These can be set by using the PLATFORM variable in the CLI when running make.
When make is run without any overriding PLATFORM variables set, make defaults 
the build for the MSP432 platform which uses the arm toolchain
(arm-none-linux-gnueubi).

Verbose comments are provided in the Makefile and sources.mk to explain what is
going on in them

© 2018 Ankush Burman
