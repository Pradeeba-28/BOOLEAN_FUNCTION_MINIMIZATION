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

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.   

module ex2 (a,b,c,d,w,x,y,z,f1,f2);  
input a,b,c,d,w,x,y,z;  
output f1,f2;  
assign f1 = ~a&~b&~c&~d | a&~c&~d | ~b&c&~d | ~a&b&c&d | b&~c&d;  
assign f2 = x&~y&z | ~x&~y&z | ~w&x&y | w&~x&y | w&x&y;  
endmodule  

Developed by: PRADEEBA V  
RegisterNumber:25009895  


**RTL**
<img width="1920" height="1080" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/ad383cf9-cf6f-4d93-a43d-599501f2c465" />  
<img width="1920" height="1080" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/533152db-3929-4e90-a0c3-4108353ab848" />  


**Timing Diagram**
<img width="1920" height="1080" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/6a489159-6c29-4f70-bced-707193958b0f" />  

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

