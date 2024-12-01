**EXP 2:BOOLEAN FUNCTION MINIMIZATION**

NAME:A.MOHAMED NIZAMUDDIN

REF NO:24900341

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.


**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher,Software – Quartus prime


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

module booleanminimization(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule



**RTL realization Output**

![wave form of boolean minimization ](https://github.com/user-attachments/assets/a809022a-69b9-44a3-9d84-0481d60cb4d0)



**RTL**

![boolean minimization screen shot](https://github.com/user-attachments/assets/cce6ce51-8d1a-41c5-9d08-b3e71bd5b014)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

