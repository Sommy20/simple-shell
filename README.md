#### Simple shell

### Description

Our shell is a simple UNIX command interpreter that replicates functionalities of the simple shell (sh). Additional functions are also included. This program was written entirely in C as a milestone project for ALX AFRICA SE.

### Installation

Clone this repository into your working directory. For best results, files should be compiled with GCC and the following flags: -Wall -Werror -Wextra -pedantic -std=gnu89

### Usage

After compilation, the resulting program can run stand-alone, either in interactive or non-interactive mode.

#### Interactive Mode

In interactive mode, simply run the program and wait for the prompt to appear. From there, you can type commands freely, exiting with either the "exit" command or ctrl-D.

#### Non-Interactive Mode

In non-interactive mode, echo your desired command and pipe it into the program like this:

```sh
echo "ls" | ./shell
```

In non-interactive mode, the program will exit after finishing your desired command(s).

#### Included Built-Ins

Our shell has support for 

#### Outside Programs


### Included Files

- main.c - functions for calling the shell and initializing the shell struct
- 

### Credits

Codes are written by Idayat Abdulkareem (idayatolaide0@gmail.com) and Chisom Chieke (https://github.comSommy20)
