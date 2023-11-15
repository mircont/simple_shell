# Simple Shell Project

A simple Unix shell implementation in C.

## Description

This project is an implementation of a basic Unix shell, allowing users to execute commands and manage processes.

## Features

- Command execution
- Simple built-in commands (e.g., `cd`, `exit`)
- Input and output redirection
- Pipeline support
- Background process execution

## Getting Started

### Prerequisites

- GCC (GNU Compiler Collection)
- Unix-like operating system (Linux, macOS)


## Tasks

Creating an entire shell project involves implementing various functionalities. Below is an outline for the initial tasks:

- Task 0: Betty would be proud
Ensure that your code follows the Betty style guide.
Check your code using betty-style.pl and betty-doc.pl.

- Task 1: Simple shell 0.1
Create a simple shell that displays a prompt and waits for the user to type a command.
Execute the command using execve and display the result.
Handle errors appropriately.
Implement basic functionality without handling arguments, special characters, or advanced features.

- Task 2: Simple shell 0.2
Extend the shell to handle command lines with arguments.

- Task 3: Simple shell 0.3
Handle the PATH.
Check if the command exists in the PATH before forking and executing.

- Task 4: Simple shell 0.4
Implement the exit built-in command to exit the shell.

- Task 5: Simple shell 1.0
Implement the env built-in command that prints the current environment.

- Task 6: Simple shell 0.1.1 (Advanced)
Write your own getline function.

- Task 7: Simple shell 0.2.1 (Advanced)
Avoid using strtok.

- Task 8: Simple shell 0.4.1 (Advanced)
Handle arguments for the built-in exit.

- Task 9: setenv, unsetenv (Advanced)
Implement the setenv and unsetenv built-in commands.

- Task 10: cd (Advanced)
Implement the cd built-in command to change the current directory.

- Task 11: ; (Advanced)
Handle the command separator ;.

- Task 12: && and || (Advanced)
Handle the logical operators && and ||.

- Task 13: alias (Advanced)
Implement the alias built-in command.

- Task 14: Variables (Advanced)
Handle variable replacement for $? and $$.

- Task 15: Comments (Advanced)
Handle comments (#).

- Task 16: File as input (Advanced)
Allow your shell to take a file as a command line argument.
Execute the commands in the file and exit.
