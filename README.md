# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by:N.Swetha
RegisterNumber:22008828
*/
Logic symbol & Truthtable
RTL realization

### Output:
### RTL
![half and full adder_page-0001](https://user-images.githubusercontent.com/122199934/214077379-bdf7dbf0-a053-4eb5-aff0-2ac8d729b186.jpg)
![half and full adder_page-0003](https://user-images.githubusercontent.com/122199934/214077492-037f9ed5-f730-48d2-996a-8323be8ad9c4.jpg)

### TIMING DIAGRAM
![half and full adder_page-0002](https://user-images.githubusercontent.com/122199934/214077601-d7d5ae7c-ada0-4c62-a2a9-c3796f90de00.jpg)
![half and full adder_page-0004](https://user-images.githubusercontent.com/122199934/214077721-4d0ec2b9-4e91-4c98-a653-ef1308ed9779.jpg)


### TRUTH TABLE 
HALF ADDER:
![image](https://user-images.githubusercontent.com/122199934/214775076-4c800755-1a3d-4ddf-9a2b-fde3fe2c5c2d.png)
FULL ADDER:
![image](https://user-images.githubusercontent.com/122199934/214775130-ec3a51c3-889b-4f1a-85d3-4ba8d5c51577.png)



### Result:
Thus the Half adder and Full adder are designed and truth tables are verified using quarts software
