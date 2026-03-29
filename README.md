# StrukDat-Mini-Project

#1
This program is a simple implementation of a stack data structure in C using an array. A stack follows the Last In, First Out (LIFO) principle, meaning the last element added is the first one to be removed. The code defines a stack with a fixed size, then provides basic operations such as 
-push (to add elements)
-pop(to remove elements)
-display(to view the stack contents). 
It also includes checks to prevent errors like overflow (adding when full) and underflow (removing when empty), making it a complete basic example of how stacks work in programming.



#2
This program is a simple implementation of a Queue data structure in C using typedef struct and an array.

A queue follows the FIFO (First In, First Out) principle, meaning the first element inserted is the first one to be removed, just like people lining up in a queue.

In this code:

A structure named Queue is created to store:
  -an array (data) for elements
  -two indices: front (start) and rear (end)

The program provides basic queue operations:
  -enqueue() = to add elements at the rear
  -dequeue() = to remove elements from the front
  -display() = to show current elements

It also includes helper functions:
  -isFull() = checks if the queue is full
  -isEmpty() = checks if the queue is empty

