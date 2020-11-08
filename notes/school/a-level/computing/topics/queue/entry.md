---
title: "Computing - Queues"
date: "2020-10-04 15:32"
---

##### What is a queue??
A dynamic data structure in which items join at the back and leave at the front.

##### Why is a queue a dynamic data structure??
Because it can contain a variable amount of data.

##### Is a queue FIFO or LIFO??
FIFO.

##### What does FIFO stand for??
First in first out.

##### What is dequeueing??
Where an item is removed from the queue.

##### What is enqueueing??
Where an item is added to the queue.

##### What variables are needed for a queue using a dynamic array??
* A pointer to the start
* A pointer to the next space

##### When implementing a queue using a dynamic array, what one thing do you do to dequeue??
Increment the pointer to the start of the queue.

##### When implementing a queue using a dynamic array, what two things do you do to enqueue??
Store the data in the next space and increment the next space pointer.

##### What is the main advantage of a dynamic array implementation of queue??
Easy to implement.

##### What is the main disadvantage of a dynamic array implementation of a queue??
Memory is never freed up

##### What variables are needed for a queue using a static array??
* A pointer to the front
* A pointer to the rear
* A variable holding the amount of items in the queue

##### When implementing a queue using a static array, what two things do you do to dequeue??
* Increment the pointer to the front of the queue
* Decrement the variable holding the amount of items in the queue

##### When implementing a queue using a static array, what three things do you do to enqueue??
* Increment the pointer to the rear of the queue
* Store the data
* Increment the variable holding the amount of items in the queue

##### What operation do you perform when a static array-based queue runs out of space??
A shuffle.

##### What is a shuffle operation in a static array-based queue??
Moving everything back into the unused space at the front of the queue.

##### What is the main advantage of a static array implementation of a queue??
Memory is reused.

##### What is the main disadvantage of a static array implementation of a queue??
The shuffle operation may be expensive.

##### What variables are needed for a circular queue??
* A pointer to the front
* A pointer to the rear
* A variable holding the amount of items in the queue

##### When implementing a circular queue, what two things do you do to dequeue??
* Increment the pointer to the front of the queue
* Decrement the variable holding the amount of items in the queue

##### When implementing a circular queue, what three things do you do to enqueue when there's still space left in the array??
* Increment the pointer to the rear of the queue
* Store the data
* Increment the variable holding the amount of items in the queue

##### When implementing a circular queue, what three things do you do to enqueue when there's no more space left at the end of the array??
* Redefine the rear of the queue pointer to the start of the array
* Store the data
* Increment the variable holding the amount of items in the queue

##### When implementing a circular queue, what one thing do you need to do when you dequeue the last space in the array??
* Reset the front of the queue pointer to the start of the array

##### How can you tell you can't add any more data in a circular queue??
The amount of data in the queue matches the length of the array.

##### What are the two types of queue implementations??
* Linear
* Circular

##### What are the two representations for a linear queue??
* A dynamic array
* A static array

##### What is the representation used for a static queue??
* A static array
