# Linux Command Line Cheat Sheet


- [Linux Command Line Cheat Sheet](#linux-command-line-cheat-sheet)
  - [Installing Python on Ubuntu from Source](#installing-python-on-ubuntu-from-source)


## Installing Python on Ubuntu from Source

The libraries and dependencies necessary to build Python:
- [build-essential](https://www.javatpoint.com/ubuntu-build-essential): The build-essentials packages are the form of meta-packages that are essential to compile software. They contain the GNU/g++ compiler collection, GNU debugger, and a few more libraries and tools that are needed for compiling a program. A few other packages, like :
  - g++: It is a GNU compiler for C++ language.
  - gcc: It is a GNU compiler for C language.
  - make: It is a helpful utility that is used to direct the program's compilation.
  - libc6-dev: It is a GNU C library. It includes the header files and development directories used for compiling general C++ and C scripts.
  - dpkg-dev: This package is used to upload, build, and unpack Debian source packages.


```sh
sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev libsqlite3-dev wget libbz2-dev

```


