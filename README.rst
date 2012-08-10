s-parse
=======

Title
=====

        Strace Analyser to parse the output of Strace Command in Linux

What it does?
=============

        S-PARSE is a strace analyzer tool. This tool will parse the output of strace command and the output will be displayed with attractive GUI. This output will be in the tabular as well as graphical form. System calls, their start and finish time, errors if any, unfinished calls, return values are displayed in tabular form. Analysis of system is done in graphcal form.


Strece Description
==================

        Strace command traces system calls and signals. It intercepts and records the system calls which are called by a process and the signals which are received by a process.The name of each system call, its arguments and its return value are printed on standard error or to the file specified with the -o option. Strace is a useful diagnostic, instructional, and debugging tool.
        Each  line  in  the  trace  contains  the system call name, followed by its arguments in parentheses and its return value. Errors (typically a return value of -1) have the errno symbol and error string appended. Signals are printed as a signal symbol and a signal string.


External Interfaces
====================
         
Tools : Git tool
 
Technology : pyhton programming


Hardware And Software Requirements
===================================

 1. Hardware:x86 compatible processor
 #. Software:Linux Operating System(Fedora 17)


Advantages
==========

 1. User readable format of Strace Output.
 #. Analysis of system calls based on time requirment, errors if any, number of system calls.
 #. Able to compair between properties of different system calls depending on analysis.


Versioning
==========

        First version will deal with the display of output of strace ls command in the tabular form. The expanded version may include graphical representation and GUI development.


Contributors
============

 1. Akanksha Patil.
 #. Jyoti Varpe.
 #. Kalyani Kulkarni.
 #. Nikita Shah.
