# lattice_z80
*A development environment for the Lattice FPGAs using Z80 CPUs*

This project is an implementation of a small processing subsystem for Lattice FPGAs (ICE40-HX8K) of a Z80 CPU, a memory controller and some peripherals. It is based on the Z80 implementation of Goran Devic's Z80 (http://baltazarstudios.com/z80-cpu/) the SDCC Z80 compiler (http://sdcc.sourceforge.net/) and the APIO open source development framework (https://github.com/FPGAwars/apio-ide)

The proyect includes all the required configuration files to assemble/compile C and ASM source files for the Z80, its integration with the RTL generation, and scrips / makefiles for CPU code simulation.
## Status
So far, all this project is only tested ona Fedora 24 Workstation linux distro, but I do not foresee any issue using any other \*nix distribution or MinGW/Cygwin with windows.
* (4/Dec/2016) At the moment of writing this readme, the processor execution cannot be fully validated on the FPGA, simulations seems o work fine, but there are still some open issues with the write and out cycles of the CPU. 



