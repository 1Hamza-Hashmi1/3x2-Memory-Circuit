3x2 Memory Circuit was Created on 5/25/21


Following is Schematic Diagram used to make 3x2 Memory Circuit:
![image](https://github.com/1Hamza-Hashmi1/3x2-Memory-Circuit/assets/146145658/2d894e65-2eb3-4558-b38f-dd59e1008fdc)

-Consists of 18 AND gates, 4 OR gates and 6 D-FlipFlops

-Can input data into bit 0 and bit 1

-Has 3 memory locations


Top Left (Momemory Compnent)

-consists of 6 D-FlipFlops

-D Flip Flop, what ever as input is whatever is at output

  -if 1, pusle clock, u get a 1 out
  
  -if 0, and dont pulse clock, out is still 1 (retains in memory)
  
  -is a memory flip flop
  
  -only changes according to clcok pulse

Middle Left (Read/Write Circuit)

-AND gates are connected to clock of D-FlipFlops

Bottom Left (memory Location Select/Address Bus))

  -have 2 inputs
  
  -4 possible combination
  
  -can have 4 possible loactions for memory, but we using only 3
  
  -slect memory location 01, 10 and 11 going left to right respectively


Middle (Memory Out)

Bottom of Middle (Switch)

  -if open its 0, triggers AND gates in the read write circuit which allows a clock


Right of Middle (Read/Write Circuit)

-allows to read whats in memonry


Right Top (LED's)

-LED's turn on in respect to what data was stored 


Explination of Circuit Configuration: https://youtu.be/qZTqvMSgNt8

Storing 2 Bits of Data in Memory Location XX: https://youtu.be/XWjaUbiDHKg
