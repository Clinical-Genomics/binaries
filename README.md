- [Purpose](#purpose)
- [Generic tools](#generic-tools)
  * [tree](#tree)
    + [How to compile](#compile-tree)

# Purpose

Useful binaries compiled on Hasta and ready to use.

# Generic tools

## tree

"Tree is a recursive directory listing program that produces a depth indented listing of files. Color is supported ala
dircolors if the LS_COLORS environment variable is set, output is to a tty, and the -C flag is used. With no arguments,
tree lists the files in the current directory. When directory arguments are given, tree lists all the files and/or
directories found in the given directories each in turn. Upon completion of listing all files/directories found, tree
returns the total number of files and/or directories listed." from man page

### How to compile

Short steps to compile it and have tree:

1. get source from: `wget http://mama.indstate.edu/users/ice/tree/src/tree-1.8.0.tgz`
2. `tar xzfv tree-1.8.0.tgz`
3. `cd tree-1.8.0/`
4. check docs: `cat INSTALL`
5. if you don't have bin yourself: `mkdir -p $HOME/bin`
5. `make && make install prefix=$HOME/`
6. `export PATH=$PATH:~/bin/`

http://mama.indstate.edu/users/ice/tree/

Binary is available in this repo. Download it and have fun!
