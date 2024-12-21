# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions.

Boolean function minimization

F1

![397908085-9d29eed3-a0d9-41cd-ace4-8cf18413dbee](https://github.com/user-attachments/assets/30514b1a-ecf7-410a-9437-2bb84490eb1c)

F1

![397908091-6eb33a06-c60e-40c6-86f9-04f9cbf09b1a](https://github.com/user-attachments/assets/b2a06237-8c43-4d78-9f5a-ed219e641e69)

Truth Table


F1

![397907437-3044bdf3-79fe-47e9-9b0d-40b33b194d9e](https://github.com/user-attachments/assets/28431796-62a1-4e60-8d5e-5a64ed6c6357)

F2

![397907421-3462c2dc-aa00-4025-810d-e43682ab83e1](https://github.com/user-attachments/assets/1ebb074e-72cd-4981-b252-b163ff3d8757)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**


Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by: GAYATHRI S 

RegisterNumber:24900444

```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```
```
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```
**RTL**

f1:

![392497040-fe01d718-b5e9-4c2a-b506-8aea7d2f07b0](https://github.com/user-attachments/assets/eba320a7-0de4-422f-8d45-bffc000dfca7)


f2:


![392497184-fb3f6222-c330-44e1-b834-62d1f1c50e46](https://github.com/user-attachments/assets/0c273d86-5747-463c-8c5f-cfcc7869ce0b)

**Timing Diagram**

f1:


![392497141-a8158992-158f-4eb2-9e79-fd7ae91008a9](https://github.com/user-attachments/assets/8db38b61-2d88-483e-9c0d-f94b0137e1aa)

f2:


![392497239-2acdb7d7-8daf-4547-8a73-9dde2ab833de](https://github.com/user-attachments/assets/f42f674e-a8e4-4431-bd15-8c461e14eec6)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

