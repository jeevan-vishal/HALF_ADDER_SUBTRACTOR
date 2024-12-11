### NAME:JEEVAN VISHAL GD
### REG NO:24900595
### EXPERIMENT:3: HALF ADDER SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

### AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

### EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

### HALF ADDER:

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)



### HALF SUBTRACTOR:

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)


### PROCEDURE:

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


### PROGRAM:
![Screenshot 2024-11-28 111946](https://github.com/user-attachments/assets/1217b5af-a639-4c23-a691-10d29a26f369)


### RTL REALIZATION OUTPUT:
![Screenshot 2024-11-28 112027](https://github.com/user-attachments/assets/481c0b6f-027d-4736-a1cf-906a4e77ebc8)

### TRUTHTABLE:
![abb1adc7-2cd8-430f-8961-0c7aaafb6407](https://github.com/user-attachments/assets/c5a31a50-4ed2-4d64-8f30-c8928c9d84e8)


### TIMING DIAGRAM:
![Screenshot 2024-11-28 115633](https://github.com/user-attachments/assets/a479ac94-2800-489b-81fa-c9b5b288e6cb)

### RESULT:
The given logic functions are implemented using and their operations are verified
Verilog programming Successfully
