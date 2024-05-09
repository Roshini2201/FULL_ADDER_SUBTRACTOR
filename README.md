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

1.Open Quartus II and create a new project.   
2.Use schematic design entry to draw the full adder circuit.      
3.The circuit consists of XOR, AND, and OR gates.       
4.Compile the design, verify its functionality through simulation.      
5.Implement the design on the target device and program it.     

**Developed by: ROSHINI S**  
**RegisterNumber:  212223240142** 

## FULL ADDER

**Program:**  

![322213549-80906e1c-545b-4d3a-9c71-99c0443828f0](https://github.com/Roshini2201/FULL_ADDER_SUBTRACTOR/assets/154105318/d2553e53-2984-461e-9eae-1fdea3a9021c)

**RTL Schematic**

![322213587-c1ca37d3-8b5f-438a-9201-d61ed5ecfe91](https://github.com/Roshini2201/FULL_ADDER_SUBTRACTOR/assets/154105318/79687066-a010-4e21-b031-5b0b22ff28d9)

**Truth Table**

![322213629-48e71c4f-ee15-4f52-ad9b-539b8141ea57](https://github.com/Roshini2201/FULL_ADDER_SUBTRACTOR/assets/154105318/1d7ad26d-6c54-4238-b38b-ab935543fc58)

**Output Timing Waveform**
![322213637-446eca87-b987-42c9-99b6-f2948129753b](https://github.com/Roshini2201/FULL_ADDER_SUBTRACTOR/assets/154105318/b1b2400c-28d6-4a2a-820f-4c9bc668ca89)

## FULL SUBTRACTOR

**Program:**

![322214361-17b1d42d-d7c4-4180-9f06-64fd3b3f8346](https://github.com/Roshini2201/FULL_ADDER_SUBTRACTOR/assets/154105318/bf3e286f-0c76-4302-bc09-95b6a99cf128)

**RTL schematic**

![322214380-719041d9-364d-4f30-bc80-7c5a17a1ab1b](https://github.com/Roshini2201/FULL_ADDER_SUBTRACTOR/assets/154105318/43cef810-c3cd-4d99-9e9c-f25507ca100c)

**truth Table**

![322214525-fa42ca06-f6a5-4930-9f16-04f22be0300d](https://github.com/Roshini2201/FULL_ADDER_SUBTRACTOR/assets/154105318/25be3347-3a5d-47c4-8559-477a2cd93710)

**Output Timing Waveform**
![322214397-157124c6-f8af-4fed-b09d-a5af7f0595aa](https://github.com/Roshini2201/FULL_ADDER_SUBTRACTOR/assets/154105318/6d533a74-e7a5-40f7-803b-acd9de1a1ff9)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



