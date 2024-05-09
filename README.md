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
**Procedure**

1.Open Quartus II and create a new project.  
2.Use schematic design entry to draw the full adder circuit.  
3.The circuit consists of XOR, AND, and OR gates.  
4.Compile the design, verify its functionality through simulation.  
5.Implement the design on the target device and program it.  

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Procedure**

1.Follow the same steps as for the full adder.  
2.Draw the full subtractor circuit using schematic design.  
3.The circuit includes XOR, AND, OR gates to perform subtraction.  
4.Compile, simulate, implement, and program the design similarly to the full adder.   
```
DEVELOPED BY : ROSHINI S
REGISTERATION NUMBER : 212223240142
```
## FULL ADDER ##  

**Program:** 

![322213549-80906e1c-545b-4d3a-9c71-99c0443828f0](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154105318/40a70f9b-58e9-4998-b590-6110eaea7a24)


**RTL Schematic**

![322213587-c1ca37d3-8b5f-438a-9201-d61ed5ecfe91](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154105318/21a5f713-f456-4c09-9bfd-f260d682b3e0)

**truth table**

![322213629-48e71c4f-ee15-4f52-ad9b-539b8141ea57](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154105318/2cf79079-9e9a-4220-bad6-fe3febd1ba11)

**Output Timing Waveform**

![322213637-446eca87-b987-42c9-99b6-f2948129753b](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154105318/f78de12b-652d-4757-b795-668b09c0f0d1)

## FULL SUBRACTOR ##

**program**

 ![322214361-17b1d42d-d7c4-4180-9f06-64fd3b3f8346](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154105318/6c2f46bf-90d7-4c21-bc78-b618a92382cb)

**RTL schematic**

![322214380-719041d9-364d-4f30-bc80-7c5a17a1ab1b](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154105318/ff9c68df-071e-4ed5-b467-786a6c4dbad7)

**Truth Table**

![322214525-fa42ca06-f6a5-4930-9f16-04f22be0300d](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154105318/e8d4e016-7b90-4382-a1e1-3fbca92da548)

**Output Timing Waveform**

![322214397-157124c6-f8af-4fed-b09d-a5af7f0595aa](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154105318/bb4b603c-5a28-4318-b108-544bbad191f0)

**Result**
Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.

