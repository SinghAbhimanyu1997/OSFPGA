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

## Day1

## FPGA INTRODUCTION

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

## DAY2

## OPENFPGA INTRO

## VPR FLOW

Packs the netlist, Placement, Routing And Timing Analysis.

![Screenshot (338)](https://user-images.githubusercontent.com/106426239/172041945-d468c185-7834-4d20-8320-78feba2c0dcb.png)

TIMING REPORT WITHOUT CONSTRAINT

![Screenshot (339)](https://user-images.githubusercontent.com/106426239/172041990-179bcd6c-3bfc-42cc-960d-327d62940f4f.png)

TIMING REPORT WITH CONSTRAINT

![Screenshot (343)](https://user-images.githubusercontent.com/106426239/172042040-6b705106-1d2d-4d64-855c-6edb2dc890ea.png)

## VTR FLOW 
RESULT OF VTR FLOW

![Screenshot (345)](https://user-images.githubusercontent.com/106426239/172042112-aefb2c86-c30e-48dc-aff0-b3d104e25900.png)

VPR RESULTS

![Screenshot (350)](https://user-images.githubusercontent.com/106426239/172042146-8fe18d67-99bf-441e-92af-c96592304832.png)

## POST SYNTHESIS SIMULATION

![Screenshot (352)](https://user-images.githubusercontent.com/106426239/172042175-4736dfdf-a5b7-4a8c-8ea3-2fb014ed9d9a.png)

RESULT OF POST SIMULATION

![image](https://user-images.githubusercontent.com/106426239/172066063-47bdfb8a-2a8b-4cd1-99a5-b032827c2bba.png)

## DAY 3 : INTRODUCTION TO RISC-V CORE PROGRAMMING IN VIVADO

RVmyht vivado rtl to synthesis

![image](https://user-images.githubusercontent.com/106426239/172066296-426a5dbf-9623-47b1-b811-971904f7bb33.png)

OUTPUT

![image](https://user-images.githubusercontent.com/106426239/172066352-a3edfe45-7ea7-44d7-bc13-7648f17b131e.png)


SYNTHESIS TO BIT-TO-BITSTREAM

UTILIZATION

![image](https://user-images.githubusercontent.com/106426239/172066481-9b04044e-3389-456f-87c4-b1b768025424.png)

SCHEMATIC

![image](https://user-images.githubusercontent.com/106426239/172066523-c8f7e3a9-372c-4b8f-bcbd-c06110fbd30e.png)


## DAY 4 INTRODUCTION TO SOFA FPGA FABRIC IP

SOFA COUNTER TIMING

![image](https://user-images.githubusercontent.com/106426239/172066769-e53e3abe-593c-4392-b391-b429e6afddc4.png)


SOFA POST IMPLIMENTAION OUTPUT

![image](https://user-images.githubusercontent.com/106426239/172066806-14aae942-d4a3-4544-9081-d0ae9156d904.png)




















