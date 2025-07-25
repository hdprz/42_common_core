# get_next_line

The ***get_next_line*** project is a foundational 42 assignment where I created a function that reads and returns a line from a file descriptor. This function, when called in a loop, allows reading a text file line by line until the end.

What I had to do:
* Create a function that returns a line read from a file descriptor
* Handle multiple file descriptors simultaneously without losing the reading thread on each of them
* Manage memory efficiently to avoid leaks
* Implement the function using only a limited set of allowed functions:
  * `read()`
  * `malloc()`
  * `free()`

Technical aspects I had to handle:
* Dynamic memory allocation for lines of unknown size
* Buffer management for efficient reading
* Proper handling of the newline character
* Clean handling of error cases and end-of-file
* Memory management to prevent leaks

What I learned:
* Deep understanding of file descriptors and reading operations
* Static variables and their use cases
* Memory management in C
* Buffer manipulation and string operations
* Edge case handling and robust error management

This project reinforced my C programming skills while introducing crucial concepts about system I/O and memory management that are fundamental to more complex projects.