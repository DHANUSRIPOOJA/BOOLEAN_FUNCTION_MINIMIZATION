# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**EQUIPMENT REQUIRED:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**THEORY:**

Boolean Function Minimization is the process of simplifying Boolean expressions to make them more efficient in terms of logic gates and hardware resources. The goal is to reduce the number of terms and variables in the Boolean function.


**LOGIC DIAGRAM:**

![image](https://github.com/user-attachments/assets/5869c5ad-5056-47b1-8e23-927f6bc2fcda)


**PROCEDURE:**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM:**

Program to implement the given logic function and to verify its operations in quartus
using Verilog programming.

    module funct1(a,b,c,d,f1);
    input a,b,c,d;
    output f1;
    assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
    endmodule


    module funct2(w,x,y,z,f2);
    intput w,x,y,z;
    output f2;
    assign f2=((~y & z)|(w & y)|(x &y));
    endmodule


**RTL REALIZATION OUTPUT:**

Boolean function minimization f1

![Screenshot 2024-12-25 184039](https://github.com/user-attachments/assets/bd13c7b3-9b0e-4884-be30-8996ceb18277)

Bollean function minimization f2

![Screenshot 2024-12-25 184048](https://github.com/user-attachments/assets/6ec0c01d-91b9-403d-99f1-7a953230517d)


**RTL WAVEFORM:**


Boolean function minimization f1

![Screenshot 2024-12-25 193651](https://github.com/user-attachments/assets/a53aa46c-3807-4df3-9689-a5257be9b838)

Boolen function minimization f2

![Screenshot 2024-12-25 193820](https://github.com/user-attachments/assets/5ce8ff6c-95c8-4fac-ae75-73f179d966a5)

**RESULT:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

**DEVELOPED BY: K DHANUSRI POOJA**

**REGISTRATION NO: 24011393**

