# Max Priority Queue using Linked List

This C++ program implements a max priority queue using a linked list data structure. It allows inserting elements with integer values and popping the element with the maximum value efficiently.

## Classes Implemented

### Node
- Represents a node in the linked list.
- Contains an integer value and a pointer to the next node.

### MaxPriorityQueueLinkedList
- Implements the max priority queue using a linked list.
- Supports operations like push, pop, isEmpty, getSize, and print.

## Functionality

- **push(i)**: Inserts a new node with value `i` into the priority queue.
- **pop()**: Removes and returns the node with the maximum value from the priority queue.
- **isEmpty()**: Checks if the priority queue is empty.
- **getSize()**: Returns the current size of the priority queue.
- **print()**: Prints the elements of the priority queue.

## Test Function

- **testMe()**: This function tests various functionalities of the priority queue, including push, pop, isEmpty, getSize, and stress testing.

## Main Function

The `main()` function provides an interactive interface to interact with the priority queue. It allows users to push positive numbers into the queue and pop the maximum value by entering a negative number.

## Running the Program

Compile and run the provided code. Follow the prompts to push positive integers into the priority queue and pop the maximum value by entering a negative number. Alternatively, uncomment the `testMe()` function call to run automated tests.

## Testing

The `testMe()` function evaluates the correctness of the priority queue implementation. It tests functionalities such as pushing, popping, checking if the queue is empty, getting the size, and stress testing with random inputs.

Feel free to explore and modify the code as needed.
