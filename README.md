# Traffic_light_controller_Synthesis

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
![Screenshot 2024-11-23 154622](https://github.com/user-attachments/assets/eb1b1862-772f-47c5-9449-486d7931b7d7)

## Synthesis RTL Schematic :
![Screenshot 2024-11-23 154629](https://github.com/user-attachments/assets/7deb4f37-005e-40a1-b35e-b7d8cab92da3)

## Area report:
![Screenshot 2024-11-23 154638](https://github.com/user-attachments/assets/8db379a0-5728-48fe-925c-f3399bcd1881)

## Power Report:
![Screenshot 2024-11-23 154648](https://github.com/user-attachments/assets/58bb1683-076c-4b52-940c-b6e033e74615)

## Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
