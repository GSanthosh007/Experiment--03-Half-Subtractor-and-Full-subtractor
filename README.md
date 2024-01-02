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
## Program:
![Screenshot 2024-01-02 133054](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/8467ea7f-c38f-4d2e-b51e-6a4c733b33c9)



## Tabletable
![Screenshot 2024-01-02 131150](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/79a00328-e46f-4a6f-9fbe-c4f8e3a99766)
## RTL
![Screenshot 2024-01-02 131415](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/48a35016-fde6-46a0-8044-6ba96593fc6a)
## Timing Diagram
![Screenshot 2024-01-02 131508](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/5f9ecd22-de90-4660-b1e5-c753a425cef4)


## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure
Write the detailed procedure here 
## Program:
![Screenshot 2024-01-02 133147](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/9bd60a05-6300-44b9-a8d8-7c9a15d10e77)

Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: SANTHOSH G
RegisterNumber:  212223240152
*/
## Truthtable
![Screenshot 2024-01-02 131917](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/68a34d85-f1e5-4f0d-965f-517f089ec3a6)




##  RTL realization
[Screenshot 2024-01-02 132035](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/215df764-a912-43fe-b4b5-23d1bb7ccde2)


## Timing diagram 
![Screenshot 2024-01-02 133231](https://github.com/GSanthosh007/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147527586/d0783e50-4543-4529-bd24-84c6692458c4)

## Result:!
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
