[TOC]

# Shell programming

## Basic

### Linux Shell

- Bourne shell(sh)
- C shell(csh, tcsh)
- Korn shell(ksh)
- Bourn-again shell(bash)



### Command

- `$ cat /etc/shells` - checking shell list
- `$ echo $SHELL` - checking current shell
- `$ cat /etc/passwd` - checking login shell
- `$ sudo chsh {USER_NAME}` - changing login shell



## Variable

- no need to define
- start with _ or alphabet, composed with _, alphabet, number



### Command

- `$ varname=value` - declaration

- `$ echo $varname` - checking variable's value
- `$ set` - checking variable list

- `$ unset varname` - deleting variable
- `$ export VAR_NAME=value` - declaring environment variable
- `$ env` - checking environment variable list

