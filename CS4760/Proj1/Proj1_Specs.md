# Unix System Calls and Library Functions

The goal of this homework is to become familiar with the environment in hoare while practicing system calls. I’ll like to see the use of perror and getoptin this submission. Do Exercise 3.8 (p. 87) in your text by Robbins/Robbins.

The exercise expands on the process chain of Program 3.1 in the book. So, you will need to study that code well. The *process chain* is a vehicle to experiment with wait(2)and with sharing of devices. All of the processes in the chain created by Program 3.1 sharestdin, stdout, and stderr.

Your program should give some meaningful error messages. The format for error messages should be:

my_prog: Error: Detailed error message

where my_prog is actually the name of the executable (argv[0]) that you are trying to execute.