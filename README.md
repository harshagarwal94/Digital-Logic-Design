# Digital-Logic-Design
Digital Logic Design is a 4 credit course taught in Btech at VIT (Vellore Institute of Technology)
(VIT BHOPAL UNIVERSITY)

### Course Instructor - Dr. Maheshwar R. 

#Overview



(1)


Digital Logic Design Fundamentals :
Number Systems – Positional number systems, Number base conversions
between binary, octal , decimal and hexadecimal numbers – Unsigned and Signed
binary number systems.
Boolean Algebra : Basic definitions, theorems and properties of Boolean Algebra
Boolean functions – canonical and standard forms –Digital logic gates –
Introduction to digital logic families (RTL , TTL,ECL and CML)



(2)


Combinational Logic Design :
Gate Level minimization – SOP and POS forms – The Karnaugh’s map method –
Four and Five variable functions – don’t care conditions.
Combinational Logic Functions: Analysis and design procedure – Non-arithmetic
logic functions – MUX, DEMUX, Code converters,Encoders, decoders,Parity
checker and generator. Arithmetic Circuits – Adders, subtractors, BCD adder and
Multiplier



(3)


Sequential Logic Circuits : 
Introduction – Synchronous sequential logic –
Latches &amp; Flip-flops – SR, D, JK and T – characteristic equations &amp; wave forms
– Analysis and design procedure – State diagram –state reduction – state
assignment



(4)


Registers, Counters &amp; FSMs : 
Ripple counter and synchronous counter –
Design procedure for synchronous MOD counters – UP/DOWN counter- Johnson
&amp; Ring Counters - Shift registers – SISO, SIPO,PISO,POPI.
Finite State Machine : Mealy and Moore machine – Design of sequence
detectors.



(5)


Hardware Description Language : 
Verilog HDL - Lexical Conventions -Ports
and Modules, Gate Level Modeling, Operators, Data Flow Modeling, Behavioral
level Modeling, Testbench.
Modeling of Combinational and Sequential Logic Circuits using Verilog HDL.

### Gray Converter

```
You all know about gray converter. For ex, in 3 bits, 0 to 7 will be 000,001,010,011,100,101,110 and 111.
Now the gray conversion of above 0 to 7 numbers will be as follows:

0 - 000 - put first bit (most significant bit) 0 as it is, then the next bit is also 0 - so no change -
so retain 0 - then the next bit is also 0 - so no change - so retain 0 - hence finally 000 in decimal remains 000 in gray also.

1- 001 - put first bit (most significant bit) 0 as it is, then the next bit is also 0 - so no change - 
so retain 0 - then the next bit is 1 - so there is a change - so put 1 - hence finally 001 in decimal remains 001 in gray also.

2- 010 - put first bit (most significant bit) 0 as it is, then the next bit is 1 - so there is change - 
so change 1 - then the next bit is 0 - so there is a change - so put 1 - hence finally 010 in decimal remains 011 in gray.

3- 011 - put first bit (most significant bit) 0 as it is, then the next bit is 1 - so there is change
- so change 1 - then the next bit is 1 - so no change - so put 0 - hence finally 011 in decimal remains 010 in gray.

Similarly, please proceed for 4,5,6,7..

0 to 7 in decimal will change to 0,1,3,2,6,7,5,4

```

# Disclaimer
```
* For Educational Purpose 
* harshagarwal94/Digital-Logic-Design is MIT Licensed 
```
