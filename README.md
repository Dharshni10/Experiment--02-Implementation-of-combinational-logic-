# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
## Equipments Required:

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

## Theory:
 
A combinational circuit is a circuit in which the output depends on the present combination of
inputs. Combinational circuits are made up of logic gates. The output of each logic gate is
determined by its logic function. Combinational circuits can be made using various logic gates,
such as AND gates, OR gates, and NOT gates.

## Procedure:

Create a New Project: Open Quartus and create a new project by selecting "File" > "New Project
Wizard." Follow the wizard's instructions to set up your project, including specifying the project
name, location, and target device (FPGA).

Create a New Design File: *Once the project is created, right-click on the project name in the
Project Navigator and select "Add New File." *Choose "Verilog HDL File" or "VHDL File," depending
on your chosen hardware description language.

Write the Combinational Logic Code: *Open the newly created Verilog or VHDL file and write the
code for your combinational logic.

4.Compile the Project:

*To compile the project, click on "Processing" > "Start Compilation" in the menu. *Quartus will
analyze your code, synthesize it into a netlist, and perform optimizations based on your target
FPGA device.

5.Analyze and Fix Errors:

*If there are any errors or warnings during the compilation process, Quartus will display them in the
Messages window.

*Review and fix any issues in your code if necessary. *View the RTL diagram.

6.Verification:

*Click on "File" > "New" > "Verification/Debugging Files" > "University Program VWF".

*Once Waveform is created Right Click on the Input/Output Panel > " Insert Node or Bus" > Click
on Node Finder > Click On "List" > Select All.

*Give the Input Combinations according to the Truth Table and then simulate the Output
Waveform.

## Program:

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by: DHARSHNI V M 

Register Number: 212223240029  

## Code:

![Exp2codei](https://github.com/Dharshni10/Experiment--02-Implementation-of-combinational-logic-/assets/145801097/91b060d1-05ac-4be8-8a90-9840be4a8a11)

![Exp2codeii](https://github.com/Dharshni10/Experiment--02-Implementation-of-combinational-logic-/assets/145801097/e2bd1379-4aec-47e5-b7b4-e4ec8d145e43)

## RTL realization:

![Exp2 f1](https://github.com/Dharshni10/Experiment--02-Implementation-of-combinational-logic-/assets/145801097/38884bf0-5ceb-4e4c-b829-d3ebc2ed7eba)

![Exp2 f2](https://github.com/Dharshni10/Experiment--02-Implementation-of-combinational-logic-/assets/145801097/2081941e-a0a7-44b9-b510-9ce629393a0c)

## Truth Table:

![Exp2 truthtable](https://github.com/Dharshni10/Experiment--02-Implementation-of-combinational-logic-/assets/145801097/b9927a32-316a-45fc-a202-5e273082e31f)

## Timing Diagram

![Exp2 f1 timing](https://github.com/Dharshni10/Experiment--02-Implementation-of-combinational-logic-/assets/145801097/e06f940b-56f3-447b-ac8b-8fd23f6fa610)

![Exp2 f2 timing](https://github.com/Dharshni10/Experiment--02-Implementation-of-combinational-logic-/assets/145801097/5fae9405-e9d4-49c7-9dd8-7edf83073269)

## Result:

Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
