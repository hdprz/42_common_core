# push_swap

The ***push_swap*** project is a 42 algorithm assignment focused on sorting data efficiently using a limited set of operations. The goal was to create a program that sorts a stack of integers using two stacks (A and B) and a specific set of allowed operations, while minimizing the number of moves required.

What I had to do:
* Create a program that calculates and displays the smallest list of instructions to sort a random list of integers
* Implement a set of allowed operations:
  * `sa` (swap a): Swap the first 2 elements at the top of stack a
  * `sb` (swap b): Swap the first 2 elements at the top of stack b
  * `ss`: `sa` and `sb` at the same time
  * `pa` (push a): Take the first element at the top of b and put it at the top of a
  * `pb` (push b): Take the first element at the top of a and put it at the top of b
  * `ra` (rotate a): Shift up all elements of stack a by 1
  * `rb` (rotate b): Shift up all elements of stack b by 1
  * `rr`: `ra` and `rb` at the same time
  * `rra` (reverse rotate a): Shift down all elements of stack a by 1
  * `rrb` (reverse rotate b): Shift down all elements of stack b by 1
  * `rrr`: `rra` and `rrb` at the same time

To achieve this, I implemented:
* Input validation and error handling for duplicate numbers and non-integer values
* Stack management using linked lists for efficient operations
* A sorting algorithm optimized for different stack sizes
* Operation counting and optimization to minimize moves

What I Learned:
* Advanced sorting algorithm design and optimization
* Stack-based data manipulation
* Efficient memory management in C
* Problem decomposition and algorithm complexity analysis
* Performance optimization techniques

Push_swap taught me the importance of algorithm efficiency and how different approaches can dramatically impact performance. It was a great exercise in thinking through complex sorting logic while working within specific constraints.
