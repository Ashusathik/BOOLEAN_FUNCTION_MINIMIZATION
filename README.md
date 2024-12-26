#EXP NO:2 BOOLEAN_FUNCTION_MINIMIZATION
DATE : 05/10/2024

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

Developed by:ASHRATHI S RegisterNumber:24900260

```
fuct1:
module ex(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
funt2:
module booleanfunction(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

**RTL realization**
function 1
![Screenshot 2024-12-26 212214](https://github.com/user-attachments/assets/71246da9-7a57-4805-a103-5aeb0f9e91da)
function 2
![Screenshot 2024-12-26 212327](https://github.com/user-attachments/assets/123c7a03-30d2-4c16-b701-523550347742)

**Output:**
![Screenshot 2024-12-26 212555](https://github.com/user-attachments/assets/5e3f9f0e-7c32-47c1-9b99-b21cf26c5f0e)
![Screenshot 2024-12-26 212657](https://github.com/user-attachments/assets/9e316d08-343c-4694-b237-c012671f3aaa)



**RTL**

**Timing Diagram**
function 1
![Screenshot 2024-12-26 212804](https://github.com/user-attachments/assets/3abb4d34-7f1c-4161-98bb-793bbe92a651)
function 2
![Screenshot 2024-12-26 213101](https://github.com/user-attachments/assets/cda63ab4-8e22-435d-8afe-7a280ec86e32)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

