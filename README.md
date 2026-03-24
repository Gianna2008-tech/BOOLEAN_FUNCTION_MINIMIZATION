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
module ex1(a,b,y1,y2,y3,y4,y5,y6);
input a,b;
output y1,y2,y3,y4,y5,y6;
and g1(y1,a,b);
or g2(y2,a,b);
nand g3(y3,a,b);
nor g4(y4,a,b);
xor g5(y5,a,b);
not g6(y6,a);
endmodule
```

**RTL realization output**
<img width="1917" height="1007" alt="Screenshot 2026-03-13 195940" src="https://github.com/user-attachments/assets/51e0a348-285b-4ddc-9cb5-fc0272d7ffcb" />



**RTL**
<img width="1901" height="1047" alt="Screenshot 2026-03-13 200510" src="https://github.com/user-attachments/assets/c2217c60-13ff-40d9-9a19-99b012c55267" />


**Timing Diagram**
<img width="1901" height="1047" alt="Screenshot 2026-03-13 200510" src="https://github.com/user-attachments/assets/4859a438-5f85-4880-b28d-a7cc9bbaadb6" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

