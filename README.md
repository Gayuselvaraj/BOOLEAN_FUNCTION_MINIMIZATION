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

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*
f1:module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
f2:module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

**RTL**
f1:![Screenshot 2024-11-03 212301](https://github.com/user-attachments/assets/c7f56a6c-9627-4c23-ac2f-e8f4ef3a33db)

f2:![WhatsApp Image 2024-12-03 at 02 16 36_4b7cd995 funct 2](https://github.com/user-attachments/assets/40fa6edd-20bf-4c4f-8c16-1eb2aef23e95)



**Timing Diagram**
f1:![Screenshot 2024-11-03 214916](https://github.com/user-attachments/assets/54e68b1a-23a5-4b8c-b59f-8e5d4c98c11c)

f2:![WhatsApp Image 2024-12-03 at 02 16 49_9665f23a funct2](https://github.com/user-attachments/assets/b1697f00-80f4-4ee6-a6a3-84a397947907)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

