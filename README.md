# project-002-4bit-ripple-carry-adder-verilog
Project 002 of SiliconSprint Labs: Design and simulation of a 4-bit ripple carry adder using Verilog HDL.

4-Bit Ripple Carry Adder Architecture

Inputs: A[3:0], B[3:0], Cin

Outputs: Sum[3:0], Cout

How it works:

The least significant bits (A0, B0) enter Full Adder0 with Cin.

FA0 produces S0 and carry C1.

C1 becomes the carry input to Full Adder1.

The process repeats through FA2 and FA3.

The final carry output from FA3 becomes Cout.

The carry signal must propagate ("ripple") from the least significant stage to the most significant stage. This makes the design simple but introduces delay proportional to the number of bits.
