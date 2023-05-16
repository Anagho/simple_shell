# SIMPLE SHELL IN C -hsh-
## DESCRIPTION
A simple shell written in C called -hsh-

This is a simple UNIX command interpreter based on bash and Sh.

## Overview

**hsh** is a sh-compatible command language interpreter that executes commands read from the standard input or from a file.

### Invocation

Usage: **hsh**
hsh is started with the standard input connected to the terminal. To start, compile all .c located in this repository by using this command:
```

gcc -Wall -Werror -Wextra -pendantic *.c -o hsh 
./hsh
```

**hsh** is allowed to be invoked interactively and non-interactively. If **hsh** is invoked with standard input not connected to a terminal, it reads and executes received commands in order.

Example:
```

$ echo "echo 'julien'" | ./hsh
'julien'
$
```


