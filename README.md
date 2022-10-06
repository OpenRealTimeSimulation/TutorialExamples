# Tutorial Examples

Included in this repo are collections of examples and demos for tutorials on power electronic system real-time simulation and modeling.
These examples and demos include Mathworks Matlab scripts to demonstrate different approaches to model and solve switching power converters in simulation and a collection of C++ and HDL projects to run real-time simulation of power converters on Xilinx FPGAs using Xilinx Vivado and the ORTiS Circuit Solver Codegen Tools.

## Conference Tutorials

These example/demo files are associated with tutorial presentations given at the following conferences so far:
  * ECCE 2022, October 9-12, in Detroit, Michigan, USA (https://www.ieee-ecce.org/2022/)
    * Tutorial held in afternoon on October 9th
  * PEDG 2022, June 26-29 in Kiel, Germany (https://pedg2022.org/)
    * Tutorial held on June 26th

## Where to Download

To download the example and demo files, you can find them under Releases of this repo.

The examples are grouped into three sessions, one for power electronics modeling for power and energy simulation, one for general power electronic systems simulation with switching models, and one for high-performance real-time simulation of power electronics simulations using FPGAs.  Each session folder comes with a README.txt file to explain their files purpose and usage.

The second session examples requires either Mathworks Matlab or GNU Octave to run.  The third session examples requires either of the following, depending on the example in question:
  * Code::Blocks C++ IDE (https://www.codeblocks.org/) and a GCC/other C++ compiler
  * Xilinx Vivado HLx 2019.2 (or later) FPGA development suite
  
 The third session examples use the ORTiS Circuit Solver Codegen Tools (binaries included with the examples).
 For the latest releases and source code of these tools, you can download them here: https://github.com/OpenRealTimeSimulation/SolverCodegen
 
 ## Acknowledgements
 
Thanks to following people for putting together these examples and demos:
 * Dr. Matthew Milton
  * Energy Routing Lab of University of South Carolina, Columbia, SC, USA
 * Dr. Andrea Benigni
  * IEK-10 of Forschungszentrum Juelich, Juelich, Germany; and RWTH Aachen Univerisity, Aachen, Germany
 * Dr. Giovanni De Carne
  * Institute of Technical Physics of Karlsruhe Institute of Technology (KIT), Eggenstein-Leopoldshafen, Germany
