---
short-description: Learning `C++` - Introduction
...

## Overview

Programming itself is a way to solve computer problems
through the expressive art of writing software instructions
that the machine can understand to achieve a goal. Here is a
post that is part of the tutorial I give many of my students.

I'm covering the essential building blocks in this series to
give a clear understanding of this puzzle, with the basics of
this programming language you should be able to put the puzzle
pieces together.

## Content

C++ is a general-purpose programming language and is widely
used nowadays for competitive programming. It has imperative,
object-oriented and generic programming features. C++ runs
on lots of platforms like Windows, Linux, Unix, Mac etc.

C++ is a middle-level language rendering it the advantage of
programming low-level (drivers, kernels) and even higher-level
applications (games, GUI, desktop apps etc.). The basic syntax
and code structure of both C and C++ are the same. 

Some of the features & key-points to note about the programming
language are as follows:

### C++ finds varied usage in applications such as:

* Operating Systems & Systems Programming. e.g. Linux-based OS (Ubuntu etc.)
* Browsers (Chrome & Firefox)
* Graphics & Game engines (Photoshop, Blender, Unreal-Engine)
* Database Engines (MySQL, MongoDB, Redis etc.)
* Cloud/Distributed Systems
* Some interesting facts about C++: 
* Here are some awesome facts about C++ that may interest you:

The name of C++ signifies the evolutionary nature of the changes from C. "++"
is the C increment operator.
* C++ is one of the predominant languages for the development of all kind of technical and commercial software.
* C++ introduces Object-Oriented Programming, not present in C. Like other things, C++ supports the four primary features of OOP: encapsulation, polymorphism, abstraction, and inheritance.
* C++ got the OOP features from Simula67 Programming language.
* A function is a minimum requirement for a C++ program to run.(at least main() function)

### Installing a compiler toolchain

C++ is a general-purpose programming language and widely used nowadays
for competitive programming. It has imperative, object-oriented and
generic programming features. 

C++ runs on lots of platform like Windows, Linux, Unix, Mac, etc.
Before we start programming with C++. We will need an environment to
be set-up on our local host system to compile and run our C++ programs
successfully.

For setting up your own personal development environment on your
local machine you need to install three important software tools:

**Text Editor:** Text Editors are type of programs used to edit or write
texts. We will use text-editors to type our C++ programs. The normal
extension of a text file is (`.txt`) but a text file containing C++
program should be saved with `.cpp` or `.cc` extension. Files ending
with the extension `.cpp` and `.cc` are called source code files and
they are supposed to contain source code written in the C++ programming
language. These extension helps the compiler to identify that the
file contains a C++ program.

Before we write with C++, one must have a text-editor installed so we can
write programs.

**Meson build system:** Meson is an open source build system meant to be
both extremely fast, and, even more importantly, as user friendly as possible.

The main design point of Meson is that every moment a developer spends writing
or debugging build definitions is a second wasted. So is every second spent
waiting for the build system to actually start compiling code. Plus it's easy
for you to focus on the samples in this notebook.

**C++ Compiler:** Once you have installed text-editor and typed and save
your program in a file with `.cpp` extension, you will need a C++
compiler to compile this file. A compiler is a computer program which
converts high-level language into machine understandable low-level
language. In other words, we can say that it converts the source code
written in a programming language into another computer language which
the computer understands. For compiling a C++ program we will need a
C++ compiler which will convert the source code written in C++ into
machine codes. Below are the details about setting up compiler on
different platforms.

**Linux Installation:** If you're using a Linux host system we will be
install the GNU GCC compiler and Meson build system. To install and
work with the GCC compiler and Meson build on your Linux machine, proceed
according to below steps for you Linux OS.

#### Ubuntu/Debian and ChromeOS

```
sudo apt-get update
sudo apt-get install python3 python3-pip g++ -y
python3 -m pip install meson ninja
```

#### Fedora

```
dnf -y update
dnf -y install python3-devel python3-pip gcc-g++
python3 -m pip install meson ninja
```

#### ArchLinux

```
pacman -Syu --noconfirm
pacman -Syu --noconfirm g++ python python-pip
python3 -m pip install meson ninja
```

**Verification:** Verification is the act or process of verifying
something is true or verifying the state of being verified. Means of
Verification are the tools used and processes followed to collect the
data necessary to measure progress. The data collected may be quantitative
or qualitative. Here we are gonna verify if we can use Meson and GNU GCC
compiler toolchain with the following steps:

```
meson --version
g++ --version
```

If you're output looks like this or close then we should be good for the next
page in this notebook.

```
michaelbrockus@penguin:~$ meson --version
0.62.0
michaelbrockus@penguin:~$ g++ --version
g++ (Debian 10.2.1-6) 10.2.1 20210110
Copyright (C) 2020 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```

## Summary

I would like to hear your feedback on what you thought about this article as
feedback is a key component of writing a good article, blog post and learning
modules such as this.

Additionally thanks for taking the time to read this.
