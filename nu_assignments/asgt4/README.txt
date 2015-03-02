Bresenham README

Michelle Beck
meeshell at csu.fullerton.edu

3/1/2015

Summary

This is a project that implements the Bresenham line rasterization algorithm. 

One file, GFXMath.h, defines a few handy utilities (read the source) and the classes that define random numbers, vectors, and matrices. 

Another file, GLFW.h, defines functions that help create the user interface.

The third file, bresenham.cpp, contains the Bresenham line rasterization algorithm. The program appears to be fully functioning with no errors or warnings (other than the warnings for the helper functions).

Building

To compile the program, run `make' on OS X and Linux or `gmake' on FreeBSD. The Makefile is compatible with GNU Make and not BSD Make. The list of make targets are:
 . all         build all (default)
 . clean       remove intermediate files, core files, backup files
 . spotless    clean + remove all dependency files

