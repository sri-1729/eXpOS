# eXpOS

## Operating System of XSM machine

This project intends to build basic kernel routines and system call for XSM machine in order to run application programs written using eXpL language (See Documentation for more information)

The system also comes with  an interface for transferring files between the XSM machine and UNIX host

### How to run?

Please install the necessary dependencies

- Debian-based distros

```
sudo apt-get install libreadline-dev flex bison make gcc wget curl
```

- Red-Hat Linux based distros

```
sudo yum install readline-devel flex flex-devel byacc make gcc wget curl
```

- Arch based Linux distros

```
sudo pacman -S readline flex bison make gcc wget curl
```

 Go to xsm directory

 Run xsm file

```
./xsm
```

Basic commands such as

- ls.xsm : to list down the programs available to run

- cp.xsm: to copy one file to other

- cat.xsm: to display the contents of a file

- rm.xsm: to remove file

- ed.xsm: basic text editor

 are implemented

`![Alt Text](https://github.com/sri-1729/eXpOS/blob/master/sample.gif)



Documentation: https://exposnitc.github.io/expos-docs/
