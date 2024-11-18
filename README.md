# EXP3: HALF ADDER AND SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

![{CCC90252-2238-47D2-B618-54EF6F5EB0CC}](https://github.com/user-attachments/assets/62268576-eaf7-4006-85fc-d1bb88b281d0)

![{80DC4668-3D53-434B-BBB3-467C448F3086}](https://github.com/user-attachments/assets/fcb6fdd5-5a1b-45db-90cb-0f0dd58d8df8)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
![{0E6999B8-0D4D-483F-BE81-D6D2035E5E07}](https://github.com/user-attachments/assets/c072c8b5-d18a-48dc-84bb-83823294f9a6)

![{64BA3AAD-7A9C-4848-B9CE-D13072D076D9}](https://github.com/user-attachments/assets/3f8eb9eb-7b2d-473d-880b-aba60234a881)


Developed by: Charithrakshi K RegisterNumber:24900651*/

**RTL Schematic**

![{E2C960CC-28AD-44CD-881B-9A70A9B1CAF5}](https://github.com/user-attachments/assets/c3531875-0e64-481d-bf6d-481cf9179b39)

![{BDB976D4-30E8-43E7-B3F6-870868F44F4E}](https://github.com/user-attachments/assets/2a34760b-5229-4736-b563-def6526bdc04)


**Output/TIMING Waveform**

![{FA05209C-6C04-4B5C-B43B-13C1FB69484E}](https://github.com/user-attachments/assets/3c893040-21d8-4c40-a3da-192106c83934)

![Screenshot 2024-11-14 141403](https://github.com/user-attachments/assets/cf1a7a83-d1ff-429f-aa67-265979151323)




**Result:*

Thus the half adder and half subtractor are studied and the truth table, logic gates are verified
