### NAME:JEEVAN VISHAL GD
### REG NO:24900595
### EXPERIMENT:3:HALF SUBTRACTORHALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

### AIM:

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

### EQUIPMENTS REQUIRED:

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

### Half ADDER:

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

### HALF SUBTRACTOR:

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor


### PROCEDURE:

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


### PROGRAM:
![Screenshot 2024-11-28 111946](https://github.com/user-attachments/assets/619bb038-cec9-452a-b448-c8370e9f0e51)


### RTL REALIZATION OUTPUT:

![Screenshot 2024-11-28 112027](https://github.com/user-attachments/assets/1eedc792-4ad7-4a1f-afe1-e08d150817db)

### TRUTHTABLE:

### HALF ADDER:
![395024334-d3395e94-060b-4052-b17c-9978433103bb](https://github.com/user-attachments/assets/4cc27cf3-2e04-456b-acdd-f2dcb019e309)

### HALF SUBTRACTOR:
![395024362-525c259f-e97a-4a47-a206-df83d8048021](https://github.com/user-attachments/assets/b9dea356-5adb-469c-b56d-c4b6ad7d7bf9)

### TIMING DIAGRAM:
![Screenshot 2024-11-28 115633](https://github.com/user-attachments/assets/c2c0d96f-db70-43cc-9490-41c765963a8d)

### RESULT:
The given logic functions are implemented using and their operations are verified
Verilog program Successfully
