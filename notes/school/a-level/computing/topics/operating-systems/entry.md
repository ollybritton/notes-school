---
title: "Computing - Operating Systems"
date: "2020-09-04 12:39"

tags: ["@?computing"]
---

##### What is the role of an operating system??
Hide the complexities of the hardware from the user.

##### Where is the OS stored on a computer??
On the hard drive.

##### How is the BIOS stored??
On the ROM.

##### What is ROM??
**R**ead **o**nly **m**emory.

##### How is the OS loaded when the computer is switched on??
The bios.

##### What is a virtual machine??
A layer of software that allows one computer to simulate another and to run more than one operating system.

##### What does API stand for??
__A__pplication __P__rogramming __I__nterface

##### What is the purpose of an API??
To hide the true complexities of an operation to the end user.

##### In what way is an API like a restaurant??
* An API is like a waiter in a restaurant
* You look at the menu and give the waiter (i.e. the API) your request
* The waiter takes the request to the kitches (i.e. the OS)
* The kitchen sends back the prepared dish via the waiter

##### What is the primary function of an OS??
Handling resource management.

##### What 4 primary resources does the OS manage??
* Processor scheduling
* Backing store management
* Memory management
* I/O devices

##### What is processor scheduling??
Where the OS controls what instructions are sent to the processor.

##### What does processor scheduling allow??
Allows programs to run simulataneously, since multiple instructions are queued.

##### What is backing storage??
Any non-volatile data storage that will hold a computer's data.

##### What is backing store management??
Allows the reading and writing of files. Keeping track of free space.

##### What is memory management??
Where the OS allocates each process some memory.

##### Where is memory allocated for processes??
On the RAM.

##### What happens if there is not enough memory on the RAM to allocate memory??
The OS allocated virtual memory on the hard drive instead.

##### What are the three primary scheduling algorithms??
* Round robin - each process uses the the processor in turn
* Shortest job next
* Priority system/queue

##### What is IO device management??
Where the OS communicates with I/O devices and handles drivers.

##### What is interrupt handling??
Where the OS deals with software and hardware interrupts.

##### What is an interrupt??
A signal from a hardware device or program that causes the operating system to stop processing its current instructions and switch priority.

##### What 4 things happen when an interrupt occurs??
1. Current processor state is saved
2. Source of the interrupt is identified
3. Appropriate interrupt service routine called
4. Processor state is restored

##### How does a keyboard create hardware interrupts??
When the keys are pressed.

##### How does a mouse create hardware interrupts??
When the mouse is moved.
