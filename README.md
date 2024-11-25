#Ex-6: Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

Synthesis RTL Schematic :
![WhatsApp Image 2024-11-21 at 22 12 08_abae1bd5](https://github.com/user-attachments/assets/7ebeb61d-7880-4f96-9a18-00c6dc9596a7)


Area report:
![WhatsApp Image 2024-11-21 at 22 12 07_ccf89870](https://github.com/user-attachments/assets/2797812c-f076-4b44-a0f3-acd1a060967b)


Power Report:
![WhatsApp Image 2024-11-21 at 22 12 08_a8a571c7](https://github.com/user-attachments/assets/0d3355dd-a8a9-4480-a808-29e1a98d0315)


Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
