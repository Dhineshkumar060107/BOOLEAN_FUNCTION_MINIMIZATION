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
```
module ex2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

Developed by:DhineshKumar.L
RegisterNumber:24900785


**RTL realization**![new exp 2 1](https://github.com/user-attachments/assets/fecfb367-72fe-43da-9785-0346f7fd3363)


**Output:**

**RTL**
![new exp2 2](https://github.com/user-attachments/assets/69895c33-5090-468c-9b0e-303e4370b8ae)



**Timing Diagram**
![new exp 2 3](https://github.com/user-attachments/assets/50b0c153-9b63-40be-8bb6-5cae4a09a572)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

