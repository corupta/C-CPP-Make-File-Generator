# C-CPP-Make-File-Generator
### A runnable that generates a makefile given a repository of .c/.cpp/.h files.

## Project Details
That's a project I've created as a university homework for the course, CMPE 230 - Systems Programming on Dec 5th, 2017.

What the project is about can be found via [Project.pdf](https://github.com/corupta/C-CPP-Make-File-Generator/blob/master/Project.pdf)

Basically, that's a python project when run on a repository including .c/.cpp/.h files it finds out how to link those files (checks out the functions inside header files and C/C++ files matching them) and creates a makefile for such linking.

Use the [generatemakefile_cpp.py](https://github.com/corupta/C-CPP-Make-File-Generator/blob/master/generatemakefile_cpp.py) for C++ projects (instead of C projects).

## Compile
No need to compile it, that'a python project.

## Run
It can be run via python generatemakefile.py or ./generatemakefile.py (if on ubuntu)
(It uses python2 not 3)

The program can be used with two or three arguments

./generatemakefile.py [path of the root folder of a .c project] [output program name]

For more details about how to use the project, check out [Report-Documentation.pdf](https://github.com/corupta/C-CPP-Make-File-Generator/blob/master/Report-Documentation.pdf)
