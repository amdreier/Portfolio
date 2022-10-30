# Portfolio
## LC4_simulator and LC4_parser 
This is a final project for a class written in C. The assembly parser takes a version of assembly language with 29 instructions and four directives and translates it into an executable .obj file which can then be fed into and “run” by the simulator program, producing a trace file of the program's execution.
The project allows for use of data memory and TRAP functions, allowing it to simulate device “input” and “output” and calls to an operating system, which can also be written for the simulator in assembly.

These programs can be downloaded and compiled using their makefiles (in the .zip) and "make all".
Sample code for the parser and simulator can be found in Test Cases.zip, with the .asm files for the parser, the .obj files as the expected output for the parser as well as input for the simulator, and the .txt files for the expected output of the simulator
Using the dif command should return no differneces between the test files and the output files.

## Menu Test.zip and MenuTest.zip
This is a personal project written in C++ along with the Qt framework to produce an interactive menu selection application. 
The purpose was to serve as a self-taught venture into GUIs with C++ and gain experience working with a GUI framework.

Menu Test.zip contains the application, however, as I don't have a lisence as a MacOS developer, to run the application you must allow it to run through the security settings.
The source code is contained in MenuTest.zip, and this code can be compiled in Qt Creator.
