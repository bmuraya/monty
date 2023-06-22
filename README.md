# monty
## Stacks, Queues - LIFO, FIFO

Stacks and queues are fundamental data structures in computer science used to organize and manage collections of items. They differ in their behavior and the order in which elements are accessed and removed.

## 1. Stack (LIFO - Last-In, First-Out):

* A stack is a linear data structure that follows the LIFO principle, meaning the last element inserted is the first one to be removed.
* It operates on the principle of "last in, first out," just like a stack of plates, where the last plate placed on top is the first one to be removed.
* The two main operations on a stack are:
 * Push: Adds an element to the top of the stack.
 * Pop: Removes the top element from the stack.
* Additional operations on stacks may include:
 * Peek (or Top): Retrieves the top element without removing it.
 * IsEmpty: Checks if the stack is empty.
* Stacks can be implemented using arrays or linked lists.

## 2. Queue (FIFO - First-In, First-Out):

* A queue is a linear data structure that follows the FIFO principle, meaning the first element inserted is the first one to be removed.
* It operates on the principle of "first in, first out," similar to a queue of people waiting in line, where the person who arrived first is the first one to be served.
* The two main operations on a queue are:
 * Enqueue: Adds an element to the end of the queue.
 * Dequeue: Removes the element from the front of the queue.
* Additional operations on queues may include:
 * *Front*: Retrieves the element at the front without removing it.
 * *IsEmpty*: Checks if the queue is empty.
*Queues can be implemented using arrays or linked lists.

 files
## TASKS
0. Implement the push (pushes an element to the stack) and pall (prints all the values on the stack, starting from the top of the stack) opcodes.
1. Implement the pint opcode (prints the value at the top of the stack, followed by a new line).
2. Implement the pop opcode (removes the top element of the stack).
3. Implement the swap opcode (swaps the top two elements of the stack).
4. Implement the add opcode (adds the top two elements of the stack).
5. Implement the nop opcode (Doesn't do anything).