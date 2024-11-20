# EXP5 : 32Bit-ALU_Synthesis

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
![IMG-20241119-WA0018](https://github.com/user-attachments/assets/7a428d75-1015-46de-8089-d20095013d7c)

#### Area report:
![IMG-20241119-WA0025](https://github.com/user-attachments/assets/1ee75d12-fb3e-42ee-9330-a57b71f0095c)

#### Power Report:
![IMG-20241119-WA0061](https://github.com/user-attachments/assets/35152a7a-8e15-4989-b65d-6564a73f60a5)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
