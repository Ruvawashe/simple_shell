#Simple Shell Project
#Task List

Task 0: Betty would be proud
Write a beautiful code that passes the Betty checks

Task 1: Simple shell 0.1
Write a UNIX command line interpreter

Task 2: Simple shell 0.2
Simple shell 0.1 + Handle command lines with arguments

Task 3: Simple shell 0.3
Simple shell 0.2 +
Handle the PATH
fork must not be called if the command doesn't exist

Task 4: Simple shell 0.4
Simple shell 0.3 +
Implement the exit built-in, that exits the shell
Usage: exit
You don't have to handle any argument to the built-in exit

Task 5: Simple shell 1.0
Simple shell 0.4 +
Implement the env built-in, that prints the current environment

Task 6: Simple shell 0.1.1
Simple shell 0.1 +
Write your own getline function
Use a buffer to read many chars at once and call the least possible the read system call
You will need to use static variables
You are not allowed to use getline
NB: You dont have to be able to move the cursor

Task 7: Simple shell 0.2.1
Simple shell 0.2 +
You are not allowed to use strtok

Task 8: Simple shell 0.4.1
Simple shell 0.4 +
Handle arguments for the built-in exit
Usage: exit status, where status is an integer used to exit the shell

Task 9: setenv, unsetenv
Simple shell 1.0 +
Implement the seteven and unsetenv builtin commands:

Task 10.1. setenv:
Initialise a new environment variable, or modify an existing one
Command syntax: setenv VARIABLE VALUE
Should print something on stderr on failure

Task 10.2. unsetenv:
Remove an environment variable
Command syntax: unsetenv VARIABLE
Should print something on stderr on failure

Task 10: cd
Shell 1.0 +

Task 11.1. Implement the builtin command cd:
Changes the current directory of the process
Command syntax: cd [DIRECTORY]
if no argument is given to cd the command must be interpreted like cd $HOME
You have to handle the command cd -
You have to update the environment variable PWD when you change directory

Task 11: ;
Simple shell 1.0 +
Handle the commands separator ;

Task 12: && and ||
Simple shell 1.0 +
Handle the && and || shell logical operators

Task 13: alias
Simple shell 1.0 +
Implement the alias builtin command

Task 14.1. Usage: alias [name[='value'] ...]
alias: Prints a list of all aliases, one per line, in the form name='value'
alias name [name2 ...]: Prints the aliases name, name2, etc 1 per line, in the form name='value'
alias name='value' [...]: Defines an alias for each name whose value is given. If name is already an alias, replaces its value with value

Task 14: Variables
Simple shell 1.0 +
Handle variables replacement
Handle the $? variable
Handle the $$ varible

Task 15: Comments
Simple shell 1.0 +
Handle comments (#)

Task 16: File as inputs
Simple shell 1.0 +
Usage: simple_shell [filename]
Your shell can take a file as a command line argument
The file contains all the commands that your shell should run before exiting
The file should contain one command per line
In this mode, the shell should not print a prompt and should not read fromstdin
