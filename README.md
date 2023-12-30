# **3x2 Memory Circuit**
>
**Explanation of Circuit Configuration:** https://youtu.be/qZTqvMSgNt8
>
**Storing 2 Bits of Data in Memory Location XX:** https://youtu.be/XWjaUbiDHKg
>
**Following is Schematic Diagram used to make 3x2 Memory Circuit:**
![image](https://github.com/1Hamza-Hashmi1/3x2-Memory-Circuit/assets/146145658/2d894e65-2eb3-4558-b38f-dd59e1008fdc)
- Consists of 18 AND gates, 4 OR gates and 6 D-FlipFlops
- Can input data into bit 0 and bit 1
- Has 3 memory locations
>
*Top Left (Momemory Compnent)*
- consists of 6 D-FlipFlops
- D Flip Flop, what ever is input is whatever is at output
  - if 1 input, pusle clock, you get a 1 output
  - if 0 input, and dont pulse clock, out is still 1 output (retains in memory)
  - is a memory flip flop
  - only changes according to clcok pulse
>
*Middle Left (Read/Write Circuit)*
- AND gates are connected to clock of D-FlipFlops
>
*Bottom Left (memory Location Select/Address Bus))*
- have 2 inputs
- 4 possible combination
- can have 4 possible loactions for memory, but we using only 3
- select memory location 01, 10 and 11 going left to right respectively
>
*Middle (Memory Out)*
>
*Bottom of Middle (Switch)*
- if switch is open, its value is 0, triggers AND gates in the read write circuit which allows a clock
>
*Right of Middle (Read/Write Circuit)*
- allows to read whats in memonry
>
*Right Top (LED's)*
- LED's turn on in respect to what data was stored 
>
