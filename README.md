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
module exp2(f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor,a,b);
input a,b;
output f_and,f_or,f_nor,f_not,f_nand,f_xor,f_xnor;
and (f_and,a,b);
or (f_or,a,b);
not (f_not,a);
nor (f_nor,a,b);
nand (f_nand,a,b);
xor (f_xor,a,b);
xnor (f_xnor,a,b);
endmodule
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: T.K.SHRIVIMAL RegisterNumber:24003314


**RTL realization**

![exp2](https://github.com/user-attachments/assets/02574d38-d70c-484e-865b-1b21ed3f1b82)


**Timing Diagram**

![Screenshot 2024-10-22 015533](https://github.com/user-attachments/assets/70b38ebf-2ec2-4695-9449-d93eb8d91899)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

