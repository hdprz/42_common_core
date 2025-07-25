# Minitalk

The ***Minitalk*** project is a 42 inter-process communication assignment where I created a data exchange program using **UNIX signals**. The core goal was to develop a client-server system capable of transmitting strings between processes using only SIGUSR1 and SIGUSR2 signals. This project introduced me to UNIX signal handling and binary data transmission protocols.

Key Features:
* Server process displays its PID on launch and waits for signals
* Client process takes a string and server PID as arguments
* Transmission of messages through binary signal conversion
* Server reconstructs and displays received messages
* Proper signal acknowledgment and error handling
* Support for special characters and Unicode

Technical Implementation:
* Binary encoding of characters using bitwise operations
* Signal handlers for SIGUSR1 (0) and SIGUSR2 (1)
* Process synchronization through signal acknowledgment
* Error checking for invalid PIDs and signal transmission
* Memory management for message reconstruction
* Efficient signal queueing and processing

What I Learned:
* Deep understanding of UNIX signals and their limitations
* Implementation of reliable communication protocols
* Process synchronization techniques
* Binary data manipulation and transmission
* Error handling in inter-process communication
* Working with system calls and signal handlers

Minitalk provided hands-on experience with fundamental UNIX IPC concepts and binary protocols, while reinforcing the importance of robust error handling in system programming.
