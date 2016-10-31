# MyShell
Interactive shell program that supports the following features:

1. Accepts command from user and executes the corresponding program with the given argument list. The program can locate and execute any valid program using absolute/relative paths, and also by searching directories in the $PATH variable.
2. Built-in commands: 
  1. timeX: prints out the process statistics of a terminated child process.
  2. exit: terminates the myshell program; once the program starts, it continuously accepts commands from user until receiving the exit command.
3. Supports two operators: & (run as background job) and | (pipe).
