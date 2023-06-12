This repository contains a collection of shell scripts that demonstrate the usage of I/O redirections and filters. The scripts are designed to showcase various techniques for manipulating input and output streams in the shell environment.

Scripts
stdin_to_file.sh: This script demonstrates the redirection of standard input (stdin) to a file. It prompts the user to enter some text, and then redirects that input to a specified file.

stdout_to_file.sh: This script shows how to redirect standard output (stdout) to a file. It generates a random number and writes it to a specified file instead of printing it to the terminal.

stderr_to_file.sh: In this script, the redirection of standard error (stderr) to a file is demonstrated. It attempts to open a non-existent file and redirects the error message to a specified file.

file_to_stdout.sh: This script illustrates the usage of input redirection, specifically reading input from a file and printing it to standard output. It reads the contents of a specified file and outputs them to the terminal.

pipe_example.sh: The script demonstrates how to use pipes to connect the output of one command to the input of another. It combines the ls and grep commands to search for a specified file in a directory.

filter_example.sh: This script showcases the usage of common shell filters, such as grep, sed, and awk. It performs basic text manipulation tasks like searching for patterns, replacing text, and extracting specific fields from a file.
