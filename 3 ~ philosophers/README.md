# philosophers

The ***philosophers*** project is a classic 42 synchronization challenge where I implemented a solution to the "Dining Philosophers Problem", dealing with concurrent programming, mutex locks, and process synchronization. The core goal was to create a program that simulates philosophers dining together while avoiding deadlocks and resource conflicts.

What I had to do:
* Create a program that simulates philosophers sitting at a round table:
  * Each philosopher needs two forks to eat
  * Forks are shared between adjacent philosophers
  * Philosophers alternate between eating, thinking, and sleeping
  * All philosophers must eat enough times to survive
* Monitor philosophers' states and detect deaths if they don't eat in time
* Handle program termination gracefully when a philosopher dies or all have eaten enough
* Ensure no deadlocks occur during execution

To achieve this, I had to:
* Implement **thread management** for each philosopher
* Use **mutexes** to protect shared resources (forks)
* Handle **race conditions** and timing issues
* Track eating cycles and philosopher states accurately
* Create a death monitoring system that checks philosophers' status

Key Features:
* Real-time simulation of multiple philosophers
* Thread-safe resource management
* Precise timing control for actions
* Death detection and program termination
* Status monitoring and reporting

What I Learned:
* Fundamentals of **concurrent programming**
* Working with threads and mutex locks
* Handling shared resources and avoiding deadlocks
* Understanding race conditions and their prevention
* Implementing timing-sensitive operations
* Managing program state across multiple threads

Philosophers was a challenging project that taught me the complexities of concurrent programming and the importance of careful resource management in multi-threaded applications.