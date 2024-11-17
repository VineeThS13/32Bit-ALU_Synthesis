# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :

![Screenshot 2024-11-17 170517](https://github.com/user-attachments/assets/4b928683-c312-4fdf-a78e-8e7a09a8965c)

#### Area report:

![Screenshot 2024-11-17 134835](https://github.com/user-attachments/assets/acacb0e7-12dd-4063-b569-69006a41abcc)

#### Power Report:

![Screenshot 2024-11-17 134814](https://github.com/user-attachments/assets/857fe046-9550-41f8-a0db-61ea8adaa062)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
