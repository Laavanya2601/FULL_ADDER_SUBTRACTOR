**NAME:LAAVANYA.R**

**REFERENCE NUMBER:24005572**

# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**
i)FULL ADDER

![Screenshot 2024-12-14 203611](https://github.com/user-attachments/assets/e0c42598-d2ef-40c0-b67f-40b951be213d)

ii)FULL SUBTRACTOR

![Screenshot 2024-12-14 203627](https://github.com/user-attachments/assets/5757c65d-d5ab-43fc-b28c-0930901bbe58)



**Procedure**
1. Type the program in Quartus software.

2. Compile and run thne program.

3. Generate the RTL schematic and save the logic diagram.

4. Create nodes for inputs and outputs to generate the timing diagram.

5. For different input combination generate the timing diagram.

**Program:**

FULL ADDER

![Screenshot 2024-12-19 113826](https://github.com/user-attachments/assets/dfc4cecb-393d-449a-9060-4fc3bebdb4f0)

FULL SUBTRACTOR

![Screenshot 2024-12-19 114132](https://github.com/user-attachments/assets/61261ce5-4fa9-41d1-94b2-cdedb5a7c659)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
*/

**RTL Schematic**

FULL ADDER

![Screenshot 2024-12-14 203658](https://github.com/user-attachments/assets/7184b80a-81a1-43b0-a932-293c342929bb)

FULL SUBTRACTOR

![Screenshot 2024-12-14 203900](https://github.com/user-attachments/assets/45f81f98-9863-45aa-9a97-52b7b3db89cb)

**Output Timing Waveform**

FULL ADDER

![Screenshot 2024-12-14 203939](https://github.com/user-attachments/assets/fd9696ae-ff19-46d3-90ee-3c3778c1a43b)

FULL SUBTRACTOR

![Screenshot 2024-12-14 203958](https://github.com/user-attachments/assets/2b1e42d4-4e6e-4e43-a2a4-7ff92adda610)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



