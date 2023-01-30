# synchronous-counter
Aim:
To design and stimulate 3 Bit synchronous counter using verilog.
Equipments required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Introduction:
A counter is a sequential circuit that goes through a prescribed sequence of states upon the application of input pulses. The input pulses called count pulses, may be clock pulses, or they may originate from an external source and may occur at prescribed intervals of time or at random.


Synchronous Counter

Synchronous counters are designed in such a way that the clock pulses are applied to the CP inputs of all the flip-flops. The common pulse triggers all the flip-flops simultaneously, rather than one at a time in succesion.

In the 3-bit synchronous counter, we have used three j-k flip-flops. As in the diagram, The J and K inputs of FF0 are connected to HIGH. The inputs J and K of FF1 are connected to the output of FF0, and the J and K inputs of FF2 are connected to the output of an AND gate, which is fed by the outputs of FF0 and FF1.

Logic Diagram:
![image](https://user-images.githubusercontent.com/123470785/215375808-6eb53b05-17e8-44c8-a8d1-4c6c880738d7.png)

Truth Table:

![image](https://user-images.githubusercontent.com/123470785/215376366-95bec0df-c673-48a7-be4e-4f04a4197262.png)
RTL Diagram:

![Screenshot_20230130_081654](https://user-images.githubusercontent.com/123470785/215376955-ff286a7f-ed3e-44f4-87da-f5e90416ca34.png)

Timing Diagram:


![Screenshot_20230129_015348](https://user-images.githubusercontent.com/123470785/215377261-39d53b33-6dd2-4432-9582-25ebb84ab530.png)

Result:

Thus the 3 bit synchronous counter is designed and stimulated using verilog code.





