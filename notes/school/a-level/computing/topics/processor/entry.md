---
title: "Computing - The Processor"
date: "2020-10-12 13:44"

tags: ["@?computing"]
---

##### In summary, what are the three things a processor does??
* Controls instructions
* Calculates instructions
* Executes instructions

##### What is the ALU??
The **A**rithmetic-**L**ogic **U**nit

##### What is the CU??
The Control Unit

##### How could you describe the ALU??
The problem solving part of the processor.

##### What's an example of the arithmetic operations??
* Add
* Subtract
* Multiply
* Divide

##### What's an example of logical operations??
* `AND`
* `OR`
* `NOT`
* `XOR`

##### What's an example of a shift operation??
* Left logical shift
* Right logical shift

##### What are the three things the ALU operates??
* Arithmetic operations
* Logical operations
* Shift operations

##### What is the purpose of the CU??
The part of the processor that coordinates the activity of all other components.

##### What's the flow chart for the role of the control unit??
$$
\texxt{accept instructions} \to \text{work out steps} \to \text{sync steps with system clock}
$$

##### What is the purpose of the clock??
Syncs operations of the processor.

##### How does the clock send signals??
As an alternating electrical signal.

##### What is the program counter??
Holds the memory address of the next instruction to be executed.

##### What does PC stand for (dedicated registers)??
Program Counter

##### What does the current instruction register store??
Holds the current instruction.

##### What does CIR stand for??
Current Instruction Register

##### What does the memory address register store??
Holds the address in memory where the processor is required to fetch or store data

##### Why are the memory address register and program counters often the same??
Because the memory address register holds the address of memory that is being inspected, which is often the address of the next instruction.

##### What does MAR stand for??
Memory Address Register

##### What does the Memory Buffer Register store??
Temporarily holds data moving between the processor and main memory

##### What does MBR stand for??
Memory Buffer Register

##### What does the status register hold??
Information about the current state of operations

##### What's an example usage of the status register??
* Holding flags indicating an overflow/underflow
* Holding flags indicating the status of the last comparison

##### What does SR stand for??
Status Register

##### When is the program counter incremented??
After the CIR is set.

##### What special-purpose register is used to store the address of what's about to be loaded from memory??
MAR

##### What special-purpose register is used to store what has just come out of main memory??
MBR

##### What are the 5 things affecting processor performance??
* Number of cores
* Cache
* Clock speed

##### What happens to the FDE cycle when there's more than one core??
Each core has its own FDE cycle.

##### Why doesn't more cores always improve performance??
Software needs to be written to work with multiple cores.

##### What is a downside of more cores??
More cores will increase the temperature.

##### What is cache??
A small amount of super fast memory that stores data frequently used by the processor.

##### Which level cache is the fastest??
Level 1

##### Most modern processors have what clock speed??
$$
2GHz - 4Ghz
$$

##### What are the 7 types of instructions a processor can execute??
* Data transfer
* Arithmetic
* Comparison
* Logical
* Branch
* Shift

##### What are the two types of branch instructions??
* Conditional
* Unconditional

##### What 2 things does an opcode consist of??
* The command
* The addressing mode

##### What is the "addressing mode"??
Specifies whether the operand is immediate addressing, direct addressing or a register.

##### How is are the bits allocated to an opcode and an operand in an instruction set??
It varies from processor to processor.

##### What must the number of bits in an instruction add up to for an instruction set??
The word length.

##### What is the limitation of the immediate addressing??
It only works with constants.

##### Why is immediate addressing the fastest??
You don't have to fetch a value from an address.
