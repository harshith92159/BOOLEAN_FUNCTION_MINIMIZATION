# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1=((~b & ~d)|(~a & b & d)|(a & b & ~c))


F2=((~y & z)|( w & y )|(x & y))

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

Developed by:S.DEEPAK

RegisterNumber:2407248

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.*/


**Output:**

**Program F1:**


```
module logic1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
```
**RTL realization**
![Screenshot 2024-11-19 185325](https://github.com/user-attachments/assets/3b0b321d-1126-41ab-9fc0-e0a542d17e79)

**Timing Diagram**
![de ex2 1](https://github.com/user-attachments/assets/d569a2e6-ba87-4009-b4f9-9d1753baff6a)

**Program F2:**


```
module logic3(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y & z)|( w & y )|(x & y));
 endmodule
```
**RTL realization**
![de ex2 2](https://github.com/user-attachments/assets/8cf86964-ede7-4e96-8638-e5d6b4024671)

**Timing Diagram**
![de _ex2 2 ](https://github.com/user-attachments/assets/2a0d65ec-5b77-4831-8bc3-2a750d728579)


Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

