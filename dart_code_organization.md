**Open DICOM<em>web</em>**
# Organization of Dart Source Code

## General Rules

1. Follow the guide-lines in [Effective Dart](https://www.dartlang.org/guides/language/effective-dart).


2. All source files should include the copyright notice in the file copyright_notice.txt file in the [SDK](https://github.com/OpenDICOMweb/sdk) repository. This file refers to the LICENSE file in the same directory.

3. In general, source files should not include the `library` directive.

4. All variables, functions, methods, Getters, Setters should have types.

## Source File Organization

All source files should have the following structure:

1. copyright notice
2. public variables (`const, final`...)
3. class(es) or functions
4. private variables or functions

## Class Organization

1. static const or final variables
2. local variables
3. Constructors
4. operators
5. getters & setters
6. methods
7. private methods
8. static methods
