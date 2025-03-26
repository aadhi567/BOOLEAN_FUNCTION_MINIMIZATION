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


**RTL realization**






**Output:**


**RTL**

Boolean function minimization f1

![image](https://github.com/user-attachments/assets/e705ddfd-6d71-46f0-aa8f-0b209e365a39)

Boolean function minimization f2

![image](https://github.com/user-attachments/assets/aaecafb3-42da-4e61-9bfb-6ba524a13e70)

**Timing Diagram**

Boolean function minimization f1

![image](https://github.com/user-attachments/assets/a7d075f8-fe8b-41b6-9e4a-ebbec2eb71cb)

Boolean function minimization f2

![image](https://github.com/user-attachments/assets/2d79c83a-7c03-44aa-9099-85f11afe2ee8)




**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

