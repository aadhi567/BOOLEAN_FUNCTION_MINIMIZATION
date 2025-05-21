# BOOLEAN_FUNCTION_MINIMIZATION

Developed by:AADHITHAN B RegisterNumber:212224040001

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

~~~
module exp2a(a,b,c,d,F1);
intput a,b,c,d;
output F1;
assign F1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule

module exp2b(w,x,y,z,F2)
intput w,x,y,z;
output F2;
assign F2=((~y&z)|(x&y)|(w&y));
endmodule
~~~




**Output:**

**RTL**

Boolean function minimization f1
![image](https://github.com/user-attachments/assets/90786a86-8a2c-4447-93e4-f461f4d7a605)

Boolean function minimization f2

![image](https://github.com/user-attachments/assets/b2e430a3-b528-4bdd-bee9-da2f6c4d24e3)


**Timing Diagram**
Boolean function minimization f1

![image](https://github.com/user-attachments/assets/333acda7-b1cb-4509-bad2-1c32c88a9f50)

Boolean function minimization f2

![image](https://github.com/user-attachments/assets/3ac4edbc-b6f8-4dcb-8043-ccfdf72811bc)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

