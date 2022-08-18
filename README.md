This is a Software Engineering (group) project of ALX Holberton school. In this project, 
Joseph Onyeike and Lehlohonolo Pretorius collaborated to simulate the functionalities of a simple Unix shell.

## About
The shell is the Linux command line interpreter. It provides an interface between the user and the kernel and executes programs called commands. For example, if a user enters `ls` then the shell executes the `ls` command.

## Simple Shell :volcano:

This simple shell includes the basic functionality of a traditional Unix-like command line user interface. Standard functions and system calls employed in simple shell include: access, execve, exit, fork, free, fstat, getline, malloc, perror, signal, stat, wait, write.

## Table of Contents
* [About](#About)
* [File Descriptions](#File-Descriptions)
* [Requirements](#Requirements)
* [More Info and Examples](#More-Info-and-Examples)
	* [Installation](#Installation)
	* [Examples](#Examples)
* [Mandatory Tasks](#Mandatory-Tasks)
* [Advanced Tasks](#Advanced-Tasks)
* [Bugs](#Bugs)
* [Authors](Authors)
* [License](#License)

## File Descriptions
* [AUTHORS](AUTHORS) - It lists the contributors of this project
* [man_1_simple_shell](man_1_simple_shell) - The Manual describing usage of the simple_shell
* [shell.h](shell.h) - The header file used in this project

## Requirements

simple shell is designed to run in the `Ubuntu 20.04 LTS` linux environment and to be compiled using the GNU compiler collection v. `gcc 12.1` with flags`-Wall, -Werror, -Wextra, -pedantic, and -std=gnu89.`

## Installation

   - Clone this repository: `git clone "https://github.com/Affluent11/simple_shell.git"`
   - Change directories into the repository: `cd simple_shell`
   - Compile: `gcc -Wall -Werror -Wextra -pedantic *.c -o hsh`
   - Run the shell in interactive mode: `./hsh`
   - Or run the shell in non-interactive mode: example `echo "pwd" | ./hsh`

## Example of Use
Run the executable in your terminal after compiling:
```
$ ./hsh
$ # This is our rendition of the shell
$ ls -al
total 100
drwxrwxr-x  3 vagrant vagrant  4096 Jul 19 22:49 .
drwxr-xr-x 14 vagrant vagrant  4096 Jul 17 22:37 ..
-rw-rw-r--  1 vagrant vagrant   144 Jul 19 17:16 AUTHORS
-rw-rw-r--  1 vagrant vagrant  2367 Jul 19 22:33 builtins2.c
-rw-rw-r--  1 vagrant vagrant  2764 Jul 19 22:14 builtins.c
-rw-rw-r--  1 vagrant vagrant   710 Jul 16 01:03 environment.c
-rw-rw-r--  1 vagrant vagrant  1217 Jul 16 03:24 errors.c
drwxrwxr-x  8 vagrant vagrant  4096 Jul 19 22:34 .git
-rwxrwxr-x  1 vagrant vagrant 32287 Jul 19 22:34 hsh
-rw-rw-r--  1 vagrant vagrant  1792 Jul 19 22:12 man_1_simple_shell
-rw-rw-r--  1 vagrant vagrant   484 Jul 15 20:09 memory_allocation.c
-rw-rw-r--  1 vagrant vagrant  1273 Jul 18 21:00 new_strtok.c
-rw-rw-r--  1 vagrant vagrant  3427 Jul 19 22:06 path.c
-rw-rw-r--  1 vagrant vagrant  2347 Jul 19 22:49 README.md
-rw-rw-r--  1 vagrant vagrant  1769 Jul 19 22:04 shell.h
-rw-rw-r--  1 vagrant vagrant  1480 Jul 18 21:15 simple_shell.c
-rw-rw-r--  1 vagrant vagrant  2111 Jul 16 01:10 strfunc.c
-rw-rw-r--  1 vagrant vagrant   719 Jul 19 21:46 tokenize.c
```
## Bugs
No known bugs exists within the program as of this writing.

## Authors
Joseph Onyeike | [@josephonyeike11@gmail.com](https://https://github.com/Affluent11)

Lehlohonolo Pretorius | [@](https://github.com)

## License
Given the open source nature of the project, no special licenses or license whatsoever is needed to use, modify, and redistribute the simple_shell program.
