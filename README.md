# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
**Boolean function**
F1


**![Screenshot 2024-12-21 123656](https://github.com/user-attachments/assets/087bb653-de9b-4cb9-9e6e-0eafeff213c9)

F2


![Screenshot 2024-12-21 123824](https://github.com/user-attachments/assets/381f75c5-7dea-4d45-be68-969c164fd7dd)

Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 


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



Developed by:Gayathri S
RegisterNumber:24900444

**RTL**

F1


![Screenshot 2024-12-21 123945](https://github.com/user-attachments/assets/333e0452-7bce-49eb-a573-6ffd02dbf560)

F2

 ![Screenshot 2024-12-21 124024](https://github.com/user-attachments/assets/680bc62a-d21c-4ddd-9adb-2d10bfac726e)
 **Output**
 
 F1
 
 
![Screenshot 2024-12-21 124253](https://github.com/user-attachments/assets/f5dd4be3-9d78-40b3-bd65-c5850fc58c2e)

F2

![Screenshot 2024-12-21 124334](https://github.com/user-attachments/assets/1e4573c5-20f5-4a5c-88eb-43787c3ff114)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

