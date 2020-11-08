---
title: "Computing - AQA Assembly"
date: "2020-10-02 12:36"

tags: ["@?computing"]
---

##### What is a register??
A temporary storage area in a CPU.

##### Simple computers have an accumulator, more complex computers have...??
Registers.

##### What does `LDR Rd, (memory ref)` do??
Load the value stored in `(memory ref)` into register `d`.

##### How many arguments does `LDR` take??
2

##### I want to put a value at a memory address into a register. What instruction should I use??
`LDR`.

##### What does `LDR R1,300` do??
Load the contents of address 300 into `R1`.

##### What does `STR Rd, (memory ref)` do??
Store the value in register `d` in the memory location specified by `(memory ref)`

##### How many arguments does `STR` take??
2

##### I want to store what's in a register in a memory address. What instruction should I use??
`STR`.

##### What does `STR R3,202` do??
Store what is in `R3` at memory address `202`.

##### What does `ADD Rd, Rn (operand)` do??
Add the value specified by `(operand)` to the value in register `n` and store the result in register `d`.

##### How many arguments does `ADD` take??
3

##### I want to add a number to a register. What instruction should I use??
`ADD`.

##### I want to increment `R1` by 3. What instruction do I use??
`ADD R1,R1,#3`

##### I want to add what's in a memory address to a register. What instruction should I use??
`ADD`.

##### What does `SUB Rd, Rn, (operand)` do??
Subtract the value specified by `(operand)` from `Rn` and store it in `Rd`.

##### How many arguments does `SUB` take??
3

##### I want to subtract a number from a register. What instruction should I use??
`SUB`.

##### I want to subtract 5 from `R7` and store the result in `R5`. What instruction should I use??
`SUB R5,R7,#5`

##### What does `MOV Rd,(operand)` do??
Move the value specified by `(operand)` into register `Rd`.

##### How many arguments does `MOV` take??
2

##### I want to put a value into a register. What instruction should I use??
`MOV`.

##### I want to put the number `7` in register `R0`. What instruction should I use??
`MOV R0,#7`

##### How can you do something similar to if-statements in assembly??
Using compare and branch.

##### What does `CMP Rn,(operand)` do??
Compare the value stored in register `Rn` with the value specified by `(operand)`.

##### How many arguments does `CMP` take??
2

##### I want to compare the contents of register `R10` with what's at memory address `300`. What instruction should I use??
`CMP R10,300`

##### What are the 4 possible results of a comparison??
* `EQ`
* `GT`
* `NE`
* `LT`

##### What does `B <label>` do??
Always branch to the instruction at position `<label>` in the program.

##### How many arguments does `B` take??
1

##### I want to always branch to the label `end` in a program. What instruction should I use??
`B end`

##### What does `B<condition> <label>` do??
Branch to `<label>` if the last comparison met the conditions specified by `<condition>`.

##### How many arguments does `B<condition>` take??
1

##### What does `BNE` mean??
Branch if not equal.

##### What's the branch instruction for being equal to zero??
`BEQ`.

##### How can you write a while loop in assembly??
* Have a label at the start of the loop
* Write condition that branches to start if met

##### What are the instructions for the 4 logical bitwise operators??
* `AND`
* `ORR`
* `EOR`
* `MVN`

##### What arguments do all the logical bitwise instructions take??
`Rd, Rn, (operand)`

##### What does `EOR R1, R3, #5` do??
Perform XOR between all the bits in `R3` and the number `5` and store the result in `R1`.

##### Why is it `EOR` instead of `XOR`??
Think "exclusive or".

##### How can you test if bits are set in assembly??
* Do a bitwise `AND` with a binary number comprised only of the bits you want to test for.
* If the result is the binary number you specified, then it matches.

##### How can you set bits in assembly??
* Do a bitwise `OR` with a binary number comprised of only the bits you want to set.

##### How can you test for odd numbers using assembly??
By doing a bitwise `AND` with `#1` and checking if the result is also `#1`.

##### I want to test if R3 is even. What are the instructions to do this??
```
AND R3,R3,#1
CMP R3,#1
BNE <where to go if even>
```

##### What are the two logical shift operators??
* `LSL`
* `LSR`

##### What does `LSL` do??
A left logical shift (increasing).

##### What does `LSR` do??
A right logical shift do??

##### What arguments do `LSL/LSR` take??
`LSL/LSR Rd,Rn,(operand)`

##### What does `LSL Rd,Rn,(operand)` do??
Left shift what's in `Rn` by `(operand)` places.

##### What does the `HALT` instruction do??
Stop the execution of the program.

##### What are the two types of `(operand)`??
* `#`, a value.
* `Rm`, the value stored in register `m`.

##### What does `Rd` represent??
"register destination".

##### What does `Rn` represent??
"register number".
