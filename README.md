# Exp-03-Implementation-of-Half-Adder-and-Full-Adder-circuit

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
Developed by: KISHORE NARAYANAN S R
RegisterNumber:  23006250
*/
Logic symbol & Truthtable
RTL realization
## CODE
### HALF ADDER:
![Exp3 ha code](https://github.com/KISHORENARAYANANSR/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148202102/2d5758a3-807c-43b7-bba6-4916d8964525)

### FULL ADDER:
![Exp3 fa code](https://github.com/KISHORENARAYANANSR/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148202102/4b4e6849-6545-4524-8baf-b3ef8275e65c)

## TRUTH TABLE:
### HALF ADDER:
![Exp3 truthtable (ha)](https://github.com/KISHORENARAYANANSR/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148202102/186288f9-6b66-45b4-83c2-4bc5791c5bf5)

### FULL ADDER:
![Exp3 truthtable (fa)](https://github.com/KISHORENARAYANANSR/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148202102/3f70e6f7-0bcc-49e3-a80b-8b2dcb3a37d4)


## OUTPUT
## RTL:
### HALF ADDER:
![Exp3 ha RTL diagram](https://github.com/KISHORENARAYANANSR/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148202102/10b21d9a-87ae-44d9-9f31-0ebc678f842e)

### FULL ADDER:
![Exp3 fa RTL diagram](https://github.com/KISHORENARAYANANSR/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148202102/aa6d1d44-a75b-49cb-ae00-fe61827ef354)

## TIMING DIAGRAM:
### HALF ADDER:
![exp3 ha wave](https://github.com/KISHORENARAYANANSR/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148202102/46712473-7726-4414-9436-5be576f59399)

### FULL ADDER:
![exp 3 fa wave](https://github.com/KISHORENARAYANANSR/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148202102/48b6ecb8-2b98-4a9e-9aab-53a973c3acaf)


## TRUTH TABLE:
### HALF ADDER:
![Exp3 truthtable (ha)](https://github.com/KISHORENARAYANANSR/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148202102/2067d8df-91d2-492c-b17f-de9fac0fffad)

### FULL ADDER:
![Exp3 truthtable (fa)](https://github.com/KISHORENARAYANANSR/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148202102/fd5f7a1c-d654-48ad-a08f-e965a573bf13)



### Result:
Thus, a half adder and full adder circuit is designed to verify its truth table in Quartus using Verilog
programming
