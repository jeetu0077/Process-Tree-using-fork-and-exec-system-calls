Project Name: Process Tree using fork and exec system calls

Project Descrition: The objective of this project is to demonstrate the working of fork and exec system calls by creating a process tree. The project is aimed at learning the use of different system calls like fork, exec, wait, getpid and getppid.

Installation:
Compile the project using command: 'make'
Run the project by passing command line arguments for depth of the tree(L) and number of children(N) using command: './assignment1 L N'

Usage:
The project can be used to learn fork and exec system calls. Child processes are differentiated from parent process using the fork return value and exec is used for each child to recursively create children of their own based on the input provided via the command line for depth and number of children.
For eg: For a input of L=2 and N=2 a parent process 'A' will create 2 child processes 'B' and 'C' which in turn will create two more processes each respectively.

Authors:
The project is created by Shaishav Hemant Oza and Jeet Pradeep Pawar.    