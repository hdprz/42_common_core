# minishell

> Group project done with [@hhecquet](https://github.com/hhecquet)

The ***minishell*** project is a crucial 42 assignment where we built a basic shell program similar to bash. This project deepened our understanding of processes, file descriptors, and command interpretation in Unix systems. The goal was to create a functional command-line interface that could handle basic shell operations while managing complex scenarios like pipes and redirections.

What we had to do:
* Display a prompt when waiting for commands
* Implement a working history system
* Handle command execution with absolute/relative paths
* Support single and double quotes
* Implement redirections (`<`, `>`, `>>`, `<<`)
* Handle pipes (`|`)
* Manage environment variables and `$?`
* Handle signals (ctrl-C, ctrl-D, ...)
* Implement built-in commands:
  * `echo` with `-n` option
  * `cd` with relative/absolute paths
  * `pwd`
  * `export`
  * `unset`
  * `env`
  * `exit`

To achieve this, we had to:
* Parse input strings into tokens and commands
* Create and manage child processes
* Handle file descriptors for redirections
* Implement proper memory management
* Design robust error handling
* Build an expandable command execution system

What We Learned:
* Deep understanding of Unix processes
* Advanced string parsing and tokenization
* Signal handling in a shell environment
* Process creation and management
* File descriptor manipulation
* Environment variable handling
* Complex memory management

Minishell was a fundamental project that brought together many core concepts of Unix system programming, requiring careful attention to detail and robust error handling throughout.