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

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:MAHASRI D
RegisterNumber:24901210
*/
```
module exe_2(f_and, f_or, f_not, f_nor, f_nand, f_xor, f_xnor,a,b);
input a,b;
output f_and, f_or, f_not, f_nor, f_nand, f_xor, f_xnor;
and(f_and, a,b);
or(f_or,a,b);
not(f_not,a);
nand(f_nand, a,b);
nor (f_nor, a,b);
xor(f_xor,a,b);
xnor(f_xnor,a,b);
endmodule
```

**RTL realization**

**Output:**
![Screenshot 2024-12-07 081144](https://github.com/user-attachments/assets/046e5c55-2968-48cb-8dcd-2b595c95714e)



**RTL**

**Timing Diagram**
![Screenshot 2024-12-07 080928](https://github.com/user-attachments/assets/863be3a9-84eb-4e4a-810c-e24ca1be291c)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

