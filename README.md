# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :NAKUL R 
 # REGISTER NUMBER :212223240102
 # DEPARTMENT : AI ML 
 # YEAR : 2ND YEAR 

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
 ![1 1](https://github.com/user-attachments/assets/075f7f45-76b4-46cc-a87e-0e33827345bf)
![2 1](https://github.com/user-attachments/assets/642a665f-c041-48e2-9451-e3b5f6eeddf5)
![3 1](https://github.com/user-attachments/assets/6228a55b-7e74-41b4-997b-bb88b3d7e52b)
![4 1](https://github.com/user-attachments/assets/e37ea7c0-d9f4-4221-b974-12744d431a2d)
![5 1](https://github.com/user-attachments/assets/d3cae710-ab24-4964-a9fe-e94aa2b80b5e)
![6 1](https://github.com/user-attachments/assets/8581ee20-b5fe-4bf3-8776-5cb6f03e0236)

# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 
![iot expt 01](https://github.com/user-attachments/assets/00c2db33-af61-4d4e-adbb-b4c3c5210ba3)

![iot expt 01 2](https://github.com/user-attachments/assets/e4ca34ab-04da-4154-b4b5-f42bbf476a05)
![iot exp 01 3](https://github.com/user-attachments/assets/b6de0fa2-c9cb-428d-a51e-81147def198f)
![iot exp 01 4](https://github.com/user-attachments/assets/b6c37d02-6105-48ad-abb8-7c478b76fead)
![iot exp 01 5](https://github.com/user-attachments/assets/417b1d8d-fb39-4e33-ba92-35766724e88f)

#Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
