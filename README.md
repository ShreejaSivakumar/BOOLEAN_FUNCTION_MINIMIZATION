BOOLEAN_FUNCTION_MINIMIZATION

DATE: 18/11/2025

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
```
module boolean_function_4var (
    input  wire A,
    input  wire B,
    input  wire C,
    input  wire D,
    output wire F
);

assign F = (~A & B) | (C & D) | (A & ~D);

endmodule
```


Developed by: SHREEJA R S 
RegisterNumber: 25017561


**RTL realization**

**Output:**
![Screenshot_18-11-2025_212259_](https://github.com/user-attachments/assets/378f7070-aecc-4326-a810-c261a5670f9b)


**RTL**

**Timing Diagram**

[boolean output.pdf](https://github.com/user-attachments/files/23609265/boolean.output.pdf)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

