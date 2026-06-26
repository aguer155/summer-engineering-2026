# Linux

## What is Linux?
Linux is an open-source kernel, which is the core part of an operating system responsible for managing hardware and system resources while allowing software to communicate with the computer. Most people use the term "Linux" to refer to complete operating systems called Linux distributions (distros), such as Ubuntu, Debian, and Fedora, which combine the Linux kernel with other software and tools.

## Why do companies use Linux?
Companies use Linux because its free and open source, reliable, secure, used in majority of web servers, cloud infastructures etc. 

## What is a terminal?
A terminal is a program that allows for text-based commands to be used. Its basically a screen for visually interacting with the computer with text. 

## What is a shell?
A shell is a program running inside the terminal that interprets commands and runs them. Common shells include bash (Bourne Again Shell) and zsh (Z Shell). 

## Difference between a terminal and a shell
The terminal is what displays the content and the shell is what actually interprets the commands and executes them. 

## What does `pwd` do?
pwd stands for Print Work Directory. It tells you where exactly you are in the file system. Think of it as a "Where am I right now?"

## What does `~` mean?
~ is a shortcut for the home directory. It is the folder that belongs to your user account. 

## What is PATH?
PATH is an environment variable. It lists folders that your shell searches through whenever a command line is typed. For example, when typing python3 or git, your shell doesnlt automatically know where those programs are, it has to search every folder listed in PATH, in order, until it finds it. 

## Why did `pipx` give me a warning?
pipx gave me a warning because it was installed in a folder that was not listen in my PATH. This meant that my shell wouldn't be able to find it and run the program. 

## Commands I learned

- pwd
- ls
- ls -la
- cd
- mkdir
- touch
- cp
- mv
- rm
- cat

## Things That Surprised Me

- macOS isn't Linux, but because it's Unix-based it shares many of the same terminal commands.
- PATH is just a list of directories.
- Programs can be installed correctly but still not run if their directory isn't in PATH.

## Questions I Still Have
N/A