![image](https://github.com/user-attachments/assets/851b8630-e398-487a-9c27-c5f97c8083eb)Developed by: r iswariya

RegisterNumber: 24900725


# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**
Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It
is fundamental to digital logic design and computer science, providing a mathematical
framework for describing logical operations and expressions

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.

**Minimization**
F1
![WhatsApp Image 2024-12-31 at 04 35 29_26b326f9](https://github.com/user-attachments/assets/2a3a3cca-57da-4108-9ddc-46085a0da2ed)
F2
![WhatsApp Image 2024-12-31 at 04 38 57_9fe9597d](https://github.com/user-attachments/assets/066daf43-0f10-4de2-8581-0bb37cbc1ea6)

**Truth Table**
![Screenshot 2024-12-31 044411](https://github.com/user-attachments/assets/541bd49a-959c-45aa-8a52-3fad567e5b5b)

**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
 F1
 module fun2a(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
 F2
 module fun2b(w,x,y,z,f2);
 input w,x,y,z;
 output f2;
 assign f2=((~y&z)|(w&y)|(x&y));
 endmodule

**RTL**
![Screenshot 2024-12-31 044739](https://github.com/user-attachments/assets/cd8d1999-29fa-41b0-baf6-aa748db422b8)

**Output:**

![Screenshot 2024-12-31 045024](https://github.com/user-attachments/assets/26890ad8-5e92-4dd5-834b-9105db7209ba)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
