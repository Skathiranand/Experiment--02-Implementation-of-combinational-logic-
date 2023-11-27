## Name: S.kathir anand
## Reg No: 23013711


# Ex No:02 Implementation of combinational logic

 
## AIM:

To implement the given logic function verify its operation in Quartus using Verilog programming.
F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
 
 
## Equipments Required:

Hardware – PCs, Cyclone II , USB flasher Software – Quartus prime

## Theory

A combinational circuit is a circuit in which the output depends on the present
combination of inputs. Combinational circuits are made up of logic gates. The output of
each logic gate is determined by its logic function. Combinational circuits can be made
using various logic gates, such as AND gates, OR gates, and NOT gates.
 
## Procedure
1. Create a New Project:

Open Quartus and create a new project by selecting "File" > "New Project
Wizard."
Follow the wizard's instructions to set up your project, including specifying the
project name, location, and target device (FPGA).

2. Create a New Design File:

Open Quartus and create a new project by selecting "File" > "New Project
Wizard."
Follow the wizard's instructions to set up your project, including specifying the
project name, location, and target device (FPGA).

3. Write the Combinational Logic Code:

*Open the newly created Verilog or VHDL file and write the code for your
combinational logic.

 4.Compile the Project:

*To compile the project, click on "Processing" > "Start Compilation" in the
menu.
*Quartus will analyze your code, synthesize it into a netlist, and perform
optimizations based on your target FPGA device.

5.Analyze and Fix Errors:

*If there are any errors or warnings during the compilation process,
Quartus will display them in the Messages window.
*Review and fix any issues in your code if necessary.
*View the RTL diagram.

6.Verification: *Click on "File" > "New" > "Verification/Debugging Files" > "University
Program VWF".

*Once Waveform is created Right Click on the Input/Output Panel > " Insert
Node or Bus" > Click on Node Finder > Click On "List" > Select All.
Program:
*Give the Input Combinations according to the Truth Table and then simulate
the Output Waveform.

## Program:

Developed by: S.kathiranand

RegisterNumber: 23013711


![Ex02(1)](https://github.com/Skathiranand/Experiment--02-Implementation-of-combinational-logic-/assets/147141136/3b5b97aa-69b6-4b37-b704-d12f7c28441e)

## RTL realization

![Ex02(2)](https://github.com/Skathiranand/Experiment--02-Implementation-of-combinational-logic-/assets/147141136/8e52335d-55dd-4c1c-ac60-32d5c2125c4e)


## Truth Table

![Ex02(3)](https://github.com/Skathiranand/Experiment--02-Implementation-of-combinational-logic-/assets/147141136/a4496a1b-05a7-4da1-a6a1-75d7149d43ef)

## Timing Diagram

![Ex02(4)](https://github.com/Skathiranand/Experiment--02-Implementation-of-combinational-logic-/assets/147141136/b61f6f47-160f-4e42-bf3b-1f8fb8cb3081)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
