# Project: Combinational Circuit Design

## Description
This project consists of designing a combinational circuit that implements the following Boolean expression:

!(!(MAJ3(a, b, !c) * XOR3(!b, c, d)) + !a)

Where MAJ3 is a function that returns the logical signal that appears most frequently in its inputs.

| a | b | c | d | !c | MAJ3 | XOR3 | !(MAJ3 * XOR3) | !a | Result |
|---|---|---|---|----|------|------|---------------|----|--------|
| 0 | 0 | 0 | 0 |  1 |  0   |   0  |        1      |  1 |    1   |
| 0 | 0 | 0 | 1 |  1 |  0   |   1  |        0      |  1 |    0   |
| 0 | 0 | 1 | 0 |  0 |  0   |   1  |        0      |  1 |    0   |
| 0 | 0 | 1 | 1 |  0 |  0   |   0  |        1      |  1 |    1   |
| 0 | 1 | 0 | 0 |  1 |  1   |   0  |        1      |  1 |    1   |
| 0 | 1 | 0 | 1 |  1 |  1   |   1  |        0      |  1 |    0   |
| 0 | 1 | 1 | 0 |  0 |  1   |   1  |        0      |  1 |    0   |
| 0 | 1 | 1 | 1 |  0 |  1   |   0  |        1      |  1 |    1   |
| 1 | 0 | 0 | 0 |  1 |  0   |   0  |        1      |  0 |    1   |
| 1 | 0 | 0 | 1 |  1 |  0   |   1  |        0      |  0 |    0   |
| 1 | 0 | 1 | 0 |  0 |  0   |   1  |        0      |  0 |    0   |
| 1 | 0 | 1 | 1 |  0 |  0   |   0  |        1      |  0 |    1   |
| 1 | 1 | 0 | 0 |  1 |  1   |   0  |        1      |  0 |    1   |
| 1 | 1 | 0 | 1 |  1 |  1   |   1  |        0      |  0 |    0   |
| 1 | 1 | 1 | 0 |  0 |  1   |   1  |        0      |  0 |    0   |
| 1 | 1 | 1 | 1 |  0 |  1   |   0  |        1      |  0 |    1   |
