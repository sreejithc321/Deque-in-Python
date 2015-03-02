# Deque

A deque, also known as a double-ended queue, is an ordered collection of items with two ends, a front and a rear, 
and the items remain positioned in the collection. New items can be added at either the front or the rear. 
It is a hybrid linear structure provides all the capabilities of stacks and queues in a single data structure.

- Deque() creates a new deque that is empty. It needs no parameters and returns an empty deque.
- add_front(item) adds a new item to the front of the deque. It needs the item and returns nothing.
- add_rear(item) adds a new item to the rear of the deque. It needs the item and returns nothing.
- remove_front() removes the front item from the deque. It needs no parameters and returns the item. The deque is modified.
- remove_rear() removes the rear item from the deque. It needs no parameters and returns the item. The deque is modified.
- is_empty() tests to see whether the deque is empty. It needs no parameters and returns a boolean value.
- size() returns the number of items in the deque. It needs no parameters and returns an integer.

### Implementing a Deque in Python 

- deque.py

### Palindrome Checker

A palindrome is a string that reads the same forward and backward, for example, radar, toot, and madam. 
The dual functionality of the deque can be used to implement a palindrome checker.

- palindrome_checker.py
