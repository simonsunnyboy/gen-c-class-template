# Source code generator for classes in ANSI C

(c) 2018 by Matthias Arndt <marndt@asmsoftware.de>

The MIT License applies to this project. See LICENSE for details.

## Abstract
This is a source code generator to create source code for ANSI C to model 
basic classes. The idea is to quickly produce a starting point to
implement object oriented software designs in ANSI C.

## System requirements

- BASH command line interpreter
- sed

## Features

- create skeleton .c and .h files for a given class name
- file names match the class name (same as in Java or C#)
- command line driven
- methods are modelled as C functions with instances through pointers
- class member variables are private and hidden by default, the user
  must provide accessor functions
- basic Doxygen support