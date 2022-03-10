# Implementation-of-Half-Adder-and-Full-Adder-circuit

## AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
1. Hardware – PCs, Cyclone II , USB flasher
2. Software – Quartus prime

## Theory

Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B
Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry. 

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin
Carry = AB + ACin + BCin

## Procedure
1. Connect the supply (+5V) to the circuit
2. Switch ON the main switch
3. 
4. If the output is 1, then the led glows.
5. 

## Program:
```
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
```
## Logic symbol & Truthtable

## RTL realization 

## Output:
![RTL](sam.png)

## Result:
Thus the half adder and full adder circuits are designed and the truth tables is verified using quartus software.
