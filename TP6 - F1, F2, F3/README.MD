# F1

F1 is a combinational circuit that implements the boolean function:

```css
F1 = not(A) and not(B) and C
```

It consists of three input ports A, B, and C, and one output port F1. The circuit uses three 2-input NAND gates and one 3-input NAND gate.

# F2

F2 is a sequential circuit that implements the boolean function:

```css
F2 = D xor Q
```

where D is the input and Q is the output. F2 uses a D flip-flop to store the output state and a 2-input XOR gate to calculate the new output based on the input and previous state.

# F3

F3 is a sequential circuit that implements the boolean function:

```css
F3 = not(A) and B and C and Q
```

where A, B, and C are the inputs, Q is the output, and the output of F3 feeds back into its own input. F3 uses a D flip-flop to store the output state, a 3-input AND gate to calculate the new output based on the inputs and previous state, and an inverter to invert the output before feeding it back into the input.