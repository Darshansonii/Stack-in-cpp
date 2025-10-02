# Stack-in-cpp

--------------------------------------------------
AIM
--------------------------------------------------
The aim of this project is to implement and demonstrate the working of a Stack data structure in C++ by performing the fundamental operations:
1. Push (Insertion)
2. Pop (Deletion)
3. Peek/Top (Accessing the top element)
4. Display (Traversing all elements)

This project helps in understanding how data is managed in a LIFO (Last In – First Out) manner and how stacks are useful in problem solving, memory management, and expression evaluation.


--------------------------------------------------
THEORY
--------------------------------------------------
A Stack is a linear data structure that follows the LIFO (Last In, First Out) principle. 
The element inserted last is the first one to be removed.

It has one pointer:
- Top → Points to the element at the top of the stack.

CHARACTERISTICS:
1. Insertion and deletion are performed only at one end (the top).
2. Access to elements is restricted (only top element can be accessed directly).
3. Can be implemented using arrays, linked lists, or STL in C++.

TYPES OF STACK IMPLEMENTATIONS:
1. Static Stack – Implemented using arrays with fixed size.
2. Dynamic Stack – Implemented using linked lists with no fixed limit.

APPLICATIONS:
- Function call management (system stack).
- Expression evaluation and syntax parsing.
- Undo/Redo operations in editors.
- Backtracking algorithms (maze, puzzles).
- Memory management in programming languages.

ADVANTAGES:
- Simple and efficient for managing data in LIFO order.
- Useful in solving recursive problems.
- Provides temporary storage for intermediate results.

LIMITATIONS:
- Fixed size in array implementation may cause overflow.
- Elements other than the top cannot be accessed directly.
- Linked list implementation uses extra memory for pointers.


--------------------------------------------------
ALGORITHM
--------------------------------------------------
PUSH (Insert)
1. Check if the stack is full (top == size - 1).
   If yes, display "Stack Overflow".
2. Else, increment top = top + 1.
3. Insert the new element at stack[top].

POP (Delete)
1. Check if the stack is empty (top == -1).
   If yes, display "Stack Underflow".
2. Else, retrieve the element at stack[top].
3. Decrement top = top - 1.

PEEK/TOP (Access Top Element)
1. If the stack is empty, display "Stack Empty".
2. Else, return stack[top].

DISPLAY
1. Check if the stack is empty.
2. If not empty, traverse from top down to 0.
3. Print all elements from top to bottom.


--------------------------------------------------
CONCLUSIONS
--------------------------------------------------
- A Stack follows the LIFO principle, where the most recently inserted element is removed first.
- The push and pop operations make stack management simple and efficient.
- Stacks are widely applicable in function calls, expression evaluation, undo/redo operations, and backtracking.
- Implementation of stacks in C++ can be done using arrays for simplicity or linked lists for flexibility.
- Learning stack implementation strengthens concepts of arrays, pointers, and recursion.
