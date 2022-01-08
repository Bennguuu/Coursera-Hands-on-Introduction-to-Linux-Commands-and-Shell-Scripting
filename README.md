# Coursera-Hands-on-Introduction-to-Linux-Commands-and-Shell-Scripting

This is my lecture notes on Hands-on Introduction to Linux Commands and Shell Scripting course offered by IBM-Coursera.

- [Coursera-Hands-on-Introduction-to-Linux-Commands-and-Shell-Scripting](#coursera-hands-on-introduction-to-linux-commands-and-shell-scripting)
- [Introduction](#introduction)
  * [Common Linux/Unix Shell Commands](#common-linux-unix-shell-commands)
  * [Running Linux on a Windows Machine](#running-linux-on-a-windows-machine)
- [Shell Scripting Basics](#shell-scripting-basics)
  * [Interactive vs Traditional Programming](#interactive-vs-traditional-programming)
  * [Scripting vs Programming Languages](#scripting-vs-programming-languages)
  * [Shell Script](#shell-script)
  * [Interpreter Directive (shebang)](#interpreter-directive--shebang-)

<small><i><a href='http://ecotrust-canada.github.io/markdown-toc/'>Table of contents generated with markdown-toc</a></i></small>


# Introduction

A shell is a powerful user interface for Unix-like operating systems. It is an interactive scripting language.
- It can interpret commands and run other programs. 
- It enables access to files, utilities, and applications. 
- It can be used to automate tasks.

Linux shell commands are used for navigating and working with files and directories. You can also use them for file compression and archiving. In this course, we will learn;
- Characteristics of Linux commands and shell scripting
- Explore the different Linux commands and their outputs
- Bash scripting
- How to schedule jobs using crontab
- How to work with filters, pipes, and variables

## Common Linux/Unix Shell Commands

Applications of shell commands include:
- Getting information
- Navigating and working with files and directories
- Printing file and string contents
- File compression and archiving
- Performing network operations
- Monitoring performance and status of the system, its components and applications
- Running batch jobs, such as ETL operations

## Running Linux on a Windows Machine

- Dual booth with a partition
- Install Linux on a virtual machine
- Use a Linux emulator (For example Git Bash)
- Windows subsystem for Linux (WSL)

# Shell Scripting Basics

## Interactive vs Traditional Programming

Interactive programming, also known as live coding, refers to any computer programming language that allows the creator to make changes to the program while it is already running. With interactive programming, the designer can make changes to the code without having to run the program over again.
In traditional programming, the coder first writes out the program and then saves it. He then runs the program on the computer. If an error occurs, it's back to the drawing board to type out new code and run the program all over again. 

## Scripting vs Programming Languages

Basically, all scripting languages are programming languages. The theoretical difference between the two is that scripting languages do not require the compilation step and are rather interpreted. For example, normally, a C program needs to be compiled before running whereas normally, a scripting language like JavaScript or PHP need not be compiled.

## Shell Script

A shell script is an executable text file in which the first line usually has the form of an interpreter directive. The interpreter directive is also known as a ‘shebang’ directive, and has the following form: 'pound, bang, interpreter' plus an optional argument. 
Interpreter is an absolute path to an executable program, and the optional argument is a string representing a single argument.
Shell scripts are scripts that invoke a shell program.

## Interpreter Directive (shebang)

Invoking Interpreters:


|     #!bin/sh                   |     Invokes Bourne Shell          |   |   |   |
|--------------------------------|-----------------------------------|---|---|---|
|     #!bin/bash                 |     Invokes Bash Shell            |   |   |   |
|     #!usr/bin/env   python3    |     Invokes Python Interpreter    |   |   |   |
|                                |                                   |   |   |   |

