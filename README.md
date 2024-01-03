# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
Write the detailed procedure here 
## Program:

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: SANTHOSH G
RegisterNumber:  2122232401
HALF SUBRACTOR:
![Screenshot 2024-01-03 063108](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/49b82ef8-61ee-4497-a5ed-e4da0d1396b3)

FULL SUBRACTOR:
![Screenshot 2024-01-03 063137](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/a99068c8-310f-4a2a-9029-88d222b24290)

TRUTH TABLE:
HALF SUBRACTOR:
![Screenshot 2024-01-03 063202](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/6b7c4ade-139d-4bbd-b547-925885a3f6a5)
FULL SUBRACTOR:
![Screenshot 2024-01-03 063303](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/4e6cbd1a-8564-4c61-9356-4ec8341fbad8)

##  RTL DIAGRAM 
HALF SUBRACTOR:
![Screenshot 2024-01-03 063352](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/5b43fd38-e3fb-41cf-a3e9-5aaf5ec52409)

FULL SUBRACTOR:
![Screenshot 2024-01-03 063417](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/f472bdd5-1fb0-4c52-959b-490f2cfe8d41)


## Timing diagram 
HALF SUBRACTOR:
![Screenshot 2024-01-03 063447](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/0ec0a908-59d3-40d9-b43e-a06dce6071c0)

FULL SUBRACTOR:
![Screenshot 2024-01-03 063525](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/2c124887-9eb9-49ee-8f0c-97f4ea92d008)

## Result:!
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
