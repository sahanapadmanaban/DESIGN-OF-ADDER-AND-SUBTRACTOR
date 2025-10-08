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

<img width="623" height="586" alt="Screenshot 2025-10-08 105315" src="https://github.com/user-attachments/assets/0ead1810-b863-459a-9002-d8ac46a76038" />


Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

**Procedure**



**Program:**

<img width="1060" height="440" alt="{2E4357C8-BCC8-4EC9-9E06-154616E6814B}" src="https://github.com/user-attachments/assets/8f89fa6d-8969-4d54-b3a1-a734ed73b472" />

<img width="801" height="532" alt="{1B2334E8-3C7B-452B-B975-D0F81DEB33D7}" src="https://github.com/user-attachments/assets/3730a0c1-d908-482e-9f78-d57bb2cbf2b9" />

DEVELOPED BY: P. SAHANA REGISTER NUMBER: 25010400

**RTL Schematic**

<img width="986" height="785" alt="{DD905B7B-EA71-488A-B979-7F5489F1AC9C}" src="https://github.com/user-attachments/assets/58aad7f6-c3c1-416a-b78e-acdc3ac1786b" />

<img width="992" height="735" alt="{855F624E-A14A-4003-87B9-084AAD8D6406}" src="https://github.com/user-attachments/assets/81e56183-f02c-4e25-9ca3-3bc9e7a01d16" />

**Output Timing Waveform**

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



