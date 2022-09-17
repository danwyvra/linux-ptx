linux-ptx
=========

admin: dan zulla (dan@zulla.me)
date: Sep 18 2022

description
-----------

the aim of this research effort is to either compile linux entirely to PTX
(NVIDIA ISA) and run it on a single GPU Core (probably slow, if possible)

- or -

engage in ongoing gcc efforts to make PTX/nvidia a compile target but 
parallize sequential assembly control flow as much as possible on multiple
GPU cores, even if this means running parts of the code simultaenously more
than once.

the goal of this project is to get linux running on a NVIDIA graphics card at
any performance, or to find accurate / prospects of feasibility.

we allocate a total of €200.000 to this repository, €0 of which has been paid.

input
-----
- consider https://bellard.org/jslinux/ and https://gpu.rocks/#/
- consider LLVM
- consider https://llvm.org/devmtg/2010-11/Rotem-CToVerilog.pdf
- consider LLVM to VHDL/Verilog for FPGAs


