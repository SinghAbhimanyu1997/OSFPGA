# OSFPGA
Open Source FPGA

![](risc-v/risc-v_banner.png)
### ABOUT THE WORKSHOP
In this workshop, I broadly cover 5 modules. The first module focuses on taking a digital design through Xilinx Vivado and programming it on the FPGA. We also did area, timing analysis, and post-implementation simulation. In the second module, we covered the OpenFPGA framework and the VTR tool flow on two designs with an example architecture. Next, we repeated these tasks for a RISC-V based processor called RVMyth then we simulated RVMyth with a testbench through Vivado and program it on a Basys3 board. We then take it through the OpenFPGA framework through Skywater OpenSource FPGA (SOFA). We also did area, timing analysis, and post implementation simulation for the processor core after taking it through SOFA. Lastly, we compared the area and timing results obtained by the design from Basys3 and VTR.
### AUTHOR OF THE WORKSHOP
#### Mr. Kunal Ghosh
Co-founder of VLSI System Design (VSD) Corporation Private Limited

#### 
### AGENDA
 [Day 1 Intro](#Day1-Intro)
  * [Part 1: FPGA introduction](#Part1-FPGA-introduction)
  * [Part 2: Vivado-counter](#Part2-Vivado-counter)
  * [Part 3: VIO Counter](#Part3-VIO-Counter)
 
 [Day OpenFPGA2](#Day2-OpenFPGA)
  * [Part 1: OpenFPGA Intro](#Part1-OpenFPGA-Intro)
  * [Part 2: VPR](#Part2-VPR)
  * [Part 3: VTR](#Part3-VTR)

 [Day 3 Introduction to RISC-V core programming on Vivado](#Day3-Introduction-to-RISC-V-core-programming-on-Vivado)
  * [Part 1: RVMyth vivado rtl-to-synthesis](#Part1-RVMyth-vivado-rtl-to-synthesis)
  * [Part 2: RVMyth Vivado synthesis-to-bitstream](#Part2-RVMyth-Vivado-synthesis-to-bitstream)

 [Day 4 Introduction to SOFA FPGA Fabric IP](#Day4-Introduction-to-SOFA-FPGA-Fabric-IP)
  * [Part 1: SOFA counter area](#Part1-SOFA-counter-area)
  * [Part 2: Fetch, decode, and execute logic](#Part2-SOFA-counter-timing)
  * [Part 3: SOFA counter post impl](#Part3-SOFA-counter-post-impl)
  * [Part 4: SOFA counter power](#Part4-SOFA-counter-power)

 [Day 5 RISC-V core on custom SOFA fabric](#Day5-RISC-V-core-on-custom-SOFA-fabric)
  * [Part 1: SOFA-RVMyth run](#Part1-SOFA-RVMyth-run)
  * [Part 2: SOFA-RVMyth timing and area](#Part2-SOFA-RVMyth-timing-and-area)
  * [Part 3: RVMyth-post impl netlist](#Part3-RVMyth-post-impl-netlist)
  * [Part 4: SOFA-RVMyth Vivado simulation](#Part4-SOFA-RVMyth-Vivado-simulation)

##Day1
##FPGA INTRODUCTION
## COUNTER SIMULATION OUTPUT
![Screenshot (325)](https://user-images.githubusercontent.com/106426239/172041414-0f35415e-f40d-4ec0-8ad0-8cc6192a4d60.png)
I/O PLANNING
![Screenshot (326)](https://user-images.githubusercontent.com/106426239/172041523-801efa2a-a01f-4697-824b-ab8282c88d88.png)
GIVING PINS TO INPUT AND OUTPUT
![Screenshot (327)](https://user-images.githubusercontent.com/106426239/172041553-2ecd1786-3bf0-466b-b285-4f5cec3592a1.png)
SCHEMATIC GENERATED
![Screenshot (329)](https://user-images.githubusercontent.com/106426239/172041578-a750ac9d-21a3-4936-9e3b-cc7e7908178e.png)
ADDING CONSTRAINT
![Screenshot (330)](https://user-images.githubusercontent.com/106426239/172041604-1bc3a859-0b0d-4b4f-9492-9247eb998f59.png)
POWER ANALYSIS
![Screenshot (331)](https://user-images.githubusercontent.com/106426239/172041639-6b918d9e-df78-49fe-8bb2-2b7989cceba1.png)
UTILIZATION REPORT
![Screenshot (332)](https://user-images.githubusercontent.com/106426239/172041670-6a30ccc5-374c-4494-a774-55fd8c0c4a16.png)




