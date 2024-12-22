# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

**TRUTH TABLE**


![Screenshot (96)](https://github.com/user-attachments/assets/a1511b6a-78e0-49db-97cf-0946a8995148)

**MINIMIZATION**

1)F1

![WhatsApp Image 2024-12-21 at 06 28 28_e6577e2d](https://github.com/user-attachments/assets/36d037ae-f2ef-43f4-85fd-9b97e0d36f5c)

2)F2

![WhatsApp Image 2024-12-21 at 06 28 47_e5a94905](https://github.com/user-attachments/assets/4d938aea-19bb-4cf3-81ca-8378318d6af0)




**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:J.P.DHAN VARSHINI

RegisterNumber:24900197

```
i)
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

ii)
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

```


**RTL**
1)F1
![exp2 1) diagram](https://github.com/user-attachments/assets/6c10293b-457d-4471-acb9-d9e55f66f8b3)


2)F2
![exp2 2) diagram](https://github.com/user-attachments/assets/f0f1c702-0d67-47ef-a2ec-7490ef44d954)



**Output:**

1)F1

![EXP2 2](https://github.com/user-attachments/assets/0ef4c28d-f5ae-443f-8768-54cfe067414c)

2)F2

![EXP2 1](https://github.com/user-attachments/assets/e3a22132-cf05-40b0-9263-2a015d65e414)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

