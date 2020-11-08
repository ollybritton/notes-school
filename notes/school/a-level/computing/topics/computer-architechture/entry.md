---
title: "Computing - Computer Organisation and Architecture"
date: "2020-09-28 13:47"

tags: ["@?computing"]
---

##### What is a computer system??
Any device that can take a set of inputs and process them into useful outputs.

##### What are the three key stages in a computer system??
$$
\text{input} \to \text{process} \to \text{output}
$$

##### What are the 4 main components of a motherboard??
* CPU
* Main memory
* Address, control and data buses
* I/O controllers

##### How do components of a motherboard communicate with one another??
Using a bus.

##### What are the three types of bus??
* Control
* Data
* Address

##### Why can't external devices be connected directly to the processor??
Because the external devices are produced by different manufacturers so they will work differently.

##### Why are I/O controllers neccessary in a motherboard??
So that the motherboard can act as an interface between the device and the computer.

##### What is the main function of an I/O controller??
Converts signals from peripheral devices into a format the computer can accept, and vice versa.

##### What burden does an I/O controller take from the CPU??
The I/O controller manages data flow to and from a device so the CPU can get on with other tasks.

##### What is the control bus??
Sends control signals to and from the processor to I/O controllers and memory.

##### What is the data bus??
Sends data between different components in the CPU.

##### What is the address bus??
Sends memory addressed from the processor to components.

##### What does uni-lateral mean??
Data can only sent one way.

##### What does bi-lateral mean??
Data can be sent both ways.

##### What is a memory read control signal??
Cause data from the addressed location to be placed on the data bus.

##### What is a memory write control signal??
Cause data on the data bus to be written into the address location.

##### What is a bus request control signal??
Indicates that a device is requesting the use of the data bus.

##### What is a bus grant control signal??
Indicates that the CPU has granted access to the data bus.

##### Who sends a bus grant control signal??
CPU.

##### What is a clock signal??
Used to synchronise operations in the CPU.

##### What is a bus in hardware??
A series of wires that transfer data signals between internal components.

##### What are the common number of lines in a bus??
* 8
* 16
* 32
* 64

##### What is a line in a bus??
One individual wire in a bus.

##### What is a word in computing??
Chunks of equal units in memory.

##### Words can be accessed by??
A unique memory address.

##### What would be the memory capacity in bytes of a machine with an $8$-line address bus and a word length of $8$ bits??
$$
8 \text{bits} \times 8 \text{lines} = 64 \text{bits} = 8 \text{bytes}
$$

##### What are the common number of words in memory??
* 8 bits
* 16 bits
* 32 bits
* 64 bits

##### What type of direction does a data bus have??
It is bi-drectional.

##### What makes a data bus bi-directional??
Data can be sent both ways along the bus.

##### What is the "width" of a data bus??
The amount of lines/wires it contains.

##### If you have a 16 line bus and a 32 bit word, how many memory access and data transfer operations will there be??
2 operations.

##### How does bus width affect overall system performance??
Because it affects how many operations there have to be to retrieve memory.

##### What type of direction is an address bus??
Uni-directional.

##### What affect oes the width of an address bus have on the system.
It determines the number of maximum possible memory addresses of the system.

##### How many addresses can a 32 bit bus support??
$$
2^{32}
$$

##### A system supports $256$ addresses. What is the width of its address bus??
$$
8
$$
