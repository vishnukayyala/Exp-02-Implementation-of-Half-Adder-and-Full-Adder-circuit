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
Developed by: 
RegisterNumber:  
*/
Logic symbol & Truthtable
RTL realization

### Output:
### HALF ADDER
![hal add pro](https://github.com/vishnukayyala/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151489368/dc288ba8-d0c7-4146-bfa0-f4895dc398e5)

### FULL ADDER
![full add pro](https://github.com/vishnukayyala/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151489368/fad54915-8015-4f2a-9317-1f36e59cd2b5)

### RTL
### HALF ADDER
![rtl hal](https://github.com/vishnukayyala/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151489368/6e0d243d-16c1-4339-96f9-d2386054d803)

### FULL ADDER
![rtl full](https://github.com/vishnukayyala/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151489368/ece2ce54-7fb7-4b51-a6be-c6bd27240b1a)

### TIMING DIAGRAM
### HALF ADDER
![hal time](https://github.com/vishnukayyala/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151489368/85db8b80-3dc0-4c9c-9137-c33556df3562)

### FULL ADDER
![ful time](https://github.com/vishnukayyala/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151489368/5cd41c9f-e803-4670-8173-ac624c3a8fbc)

### TRUTH TABLE 
### HALF ADDER
![TT hal](https://github.com/vishnukayyala/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151489368/6df910e3-8c34-4727-b5b8-628422e0d8b1)

### FULL ADDER
![TT full](https://github.com/vishnukayyala/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151489368/6618078f-5bc5-4e22-ad1d-2cd84cadf121)

### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
