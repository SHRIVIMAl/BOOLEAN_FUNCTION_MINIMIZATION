# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

![image](https://github.com/user-attachments/assets/451a04f5-8e3d-4f85-a6a6-64f04b6e113c)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module exp3(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: T.K.SHRIVIMAL RegisterNumber:24003314


**RTL realization**

![f7a4958c-0975-493d-b27d-5186c2e11fe9](https://github.com/user-attachments/assets/afd130fd-8431-42ee-ae90-cd5999de981c)

**Timing Diagram**

![f0255dec-2d4a-4bd0-ab47-3c5f60b2ae16](https://github.com/user-attachments/assets/8970ca26-d67f-41ac-b773-ae6dce7b263a)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

