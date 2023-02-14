## Description

This is the final project in the ALX low level programming. In this project, we
created a simple UNIX interpreter(SHELL). This program has the same output a
sh (/bin/sh) as well as the exactsame error output. The only difference is when
you print an error, the name of the program must be equivalent to your argv[0].

---

## Instructions

* Compiling the program:
`gcc -Wall -Werror -Wextra -pedantic *.c -o hsh
--

## Files

File|Description
---|--
- No more than 5 functions per file
- All your header files should be include guarded
- Use system calls only when you need to

---

## Tasks

### 0. README, man, AUTHORS
* Write a (README)[./README.md]
* Write a (man)[./man_1_simple_shell] for your shell.
* You should have an (AUTHORS)[./AUTHORS] file at the root of your repository,
listing all individuals having contributed content to the repository.

### 1. Betty would be proud
* Write a beautiful code that passes the Betty checks

### 2. Simple shell 0.1
* Write a UNIX command line interpreter.
* Your Shell should:
  - Display a prompt and wait for the user to type a command. A command line always ends with a new line.
    - The prompt is displayed again each time a command has been executed.
      - The command lines are simple, no semicolons, no pipes, no redirections or any other advanced features.
      	- The command lines are made only of one word. No arguments will be passed to programs.
	  - If an executable cannot be found, print an error message and display the prompt again.
	    - Handle errors.
	      - You have to handle the "end of file" condition (Ctrl+D)

### 3. Simple shell 0.2
* Handle command lines with arguments

### 4. Simple shell 0.3
* Handle the PATH

### 5. Simple shell 0.4
* Implement the exit built-in, that exits the shell
* Usage: exit
* You dont have to handle any argument to the built-in exit

### 6. Simple shell 1.0
* Implement the env built-in, that prints the current environment

### 7. Simple shell 0.1.1
* Write your own getline function

### 8. Simple shell 0.2.1

### 9. SImple shell 0.4.1
* handle argumentts for the built-in exit

### 10 setenv, unsetenv
* Implement the setenv and unsetenv builtin commands

### 11. Simple shell 1.0+
* Implement the builtin command cd
* Handle the commands seperator ;
* Handle the && and || shell logical operators
* Implement the alias builtin command
* Handle variables replacement $? and $$
* Handle comments(#)

---
## Builtins
Our shell has support for the following built-in commands:

| Command             | Definition                                                                                |
| ------------------- | ----------------------------------------------------------------------------------------- |
| exit [n]            | Exit the shell, with an optional exit status, n.                                          |
| env                 | Print the environment.                                                                    |
| setenv [var][value] | Set an environment variable and value. If the variable exists, the value will be updated. |
| alias[name[='value]]| Reads aliases name                                                                        |
| unsetenv [var]      | Remove an environment variable.                                                           |
| cd [dir]            | Change the directory.                                                                     |
| help [built-in]     | Read documentation for a built-in.


## Authors
* **Richard Rossi Adjei** - [rossiadjei](https://github.com/rossiadjei)
* **Mayowa Fedani** - [mostcharming](https://github.com/mostcharming)

---
