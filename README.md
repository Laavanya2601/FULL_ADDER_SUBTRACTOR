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

![image](https://github.com/user-attachments/assets/24cb2b1a-3e76-4bed-8786-b0661834c043)


/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
*/

**RTL Schematic**

![image](https://github.com/user-attachments/assets/47d32921-a3d2-418c-8bf9-bde9ba688b6d)

**Output Timing Waveform**

![image](https://github.com/user-attachments/assets/b3351160-61a3-480d-83a6-e9ea5e48f0bb)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



