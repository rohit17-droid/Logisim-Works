This is the implementation of a Program Counter which has a similar design to that of like in modern processors.
There are a lot of rooms for improvement in this circuit, this is just the basic level implementation.

Description:

A 4 bit shift register is used to store and shift the incoming data bits representing th PC. A 4 bit adder circuit is used to increment the PC by 1. 
A 2:1 MUX is used to select if the PC for next instruction is going to be the currently incremented PC or a new random target PC which might occur due to a JUMP/BRANCH
statement.

Future improvements:

Adding Zero flag, memory unit and other ALU units and form a full fledged ALU unit.
