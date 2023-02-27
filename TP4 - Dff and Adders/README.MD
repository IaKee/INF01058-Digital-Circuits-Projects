# Circuit Descriptions

## Circuit 1 - Full Adder

The full adder circuit is a combinational digital circuit that adds three inputs (A, B, and C) and produces two outputs (Sum and Carry). It consists of two half adders and an OR gate. The first half adder takes A and B as inputs and produces a partial sum (P) and a carry-out (C1). The second half adder takes P and C as inputs and produces the final sum (Sum) and another carry-out (C2). Finally, the OR gate takes C1 and C2 as inputs and produces the final carry-out (Carry).

## Circuit 2 - 4-Bit Ripple Carry Adder

The 4-bit ripple carry adder is a digital circuit that adds two 4-bit binary numbers and produces a 5-bit binary sum. It consists of four full adder circuits that are connected in a cascading fashion. The first full adder takes the least significant bit (LSB) of both input numbers and produces a sum and a carry-out. The second full adder takes the second LSB of both input numbers and the carry-out from the first adder as inputs, and produces another sum and carry-out. The process is repeated for the remaining two full adders until the final carry-out is produced.

## Circuit 3 - D Flip-Flop

The D flip-flop is a sequential digital circuit that stores one bit of data. It has a single input (D) and two outputs (Q and Q'). When the clock input is high, the circuit stores the value of D in Q and the complement of D in Q'. When the clock input is low, the circuit holds the previous values of Q and Q'. The D flip-flop is commonly used as a building block for more complex sequential circuits such as counters and registers.

I hope this helps you create a clear and concise description of the circuits developed for your assignment!