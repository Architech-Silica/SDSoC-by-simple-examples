# SDSoC by simple examples

Starting from a C main program targeting Zynq, we'll see how SDSoC can move functions to Programmable Logic, automatically transferring also the data to/from the hw accelerated function.

----------
This is a set of simple C code examples aiming to highlight the main SDSoC features of automatic hw acceleration of C functions.

**SDSoC is:**

- a C/C++ IDE for Zynq&MPSoC(similar to XSDK)
- a C/C++ to VHDL/Verilog function converter (Vivado High Level Synthesis invoked in background)
- a data mover instantiator (to feed data to functions implemented in Programmable Logic)
- targeting software developers (no VHDL/Verilog pre-requisites)
- able to generate a complete system (bitstream+application+OS) running Linux, FreeRTOS or Baremetal in SD card format

In essence SDSoC is a tool able to compile a C/C++ project for Cortex core, moving functions to PL on demand.

This version was written for the [Xilinx Zynq-7000 Devices](http://www.xilinx.com/products/silicon-devices/soc/zynq-7000/silicon-devices.html), using the [Avnet MicroZed Board](http://www.microzed.org).  This information is equally applicable to the next generation of [Xilinx Zynq UltraScale+ MPSoC Devices](http://www.xilinx.com/products/silicon-devices/soc/zynq-ultrascale-mpsoc/silicon-devices.html).

The provided example designs were written for the [Xilinx SDSoC Development Environment](http://www.xilinx.com/products/design-tools/software-zone/sdsoc.html).

**Included with this document:**

- Introduction to SDSoC and Lab examples
- Step by step SDSoC Lab examples
- SDSoC example designs
	- one C code line DMA
	- two vector multiplier
- Lab examples workspace, source code included


----------
## Contributions ##
Code examples are provided for your use, but please feel free to contribute your own code back to this repository via a pull request in the usual fashion.  Please fork from this repo, then create a suitably named branch in your fork before submitting back to this repo.  Please don't submit a pull request from your "master" branch.  Each new addition to the code should belong to its own submitted branch.  Thanks. 

