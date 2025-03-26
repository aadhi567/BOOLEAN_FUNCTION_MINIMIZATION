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

```

module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

```

Developed by: Aadhithan B RegisterNumber: 212224040001


**RTL realization**

**Output:**

**RTL**
Boolean function minimization f1 

![image](https://github.com/user-attachments/assets/015e44ca-91e0-4870-a658-914e89760e6f)

Boolean function minimization f2 

![image](https://github.com/user-attachments/assets/31b87fb0-f965-48ef-a3e3-92a2a050ffc7)



**Timing Diagram**

Boolean function minimization f1

![image](https://github.com/user-attachments/assets/ea682c06-3dea-4e88-afc4-dcd99fa5cdfc)

Boolean function minimization f2

![image](https://github.com/user-attachments/assets/20505437-135b-4d21-b164-0260d5529638)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

