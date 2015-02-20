GFXMath README

Michelle Beck
meeshell at csu.fullerton.edu

2/17/2015

Summary

This is project is a small vector and matrix math library for use in CS 484. 

One file, GFXMath.h, defines a few handy utilities (read the source) and the classes that define random numbers, vectors, and matrices. 

The other file GFXMath_Test.cpp is a unit test of GFXMath.h. Currently, GFXMath.h passes all of the unit tests (not the helper function tests).

Building

To compile the program, run `make' on OS X and Linux or `gmake' on FreeBSD. The Makefile is compatible with GNU Make and not BSD Make. The list of make targets are:
 . all         build all (default)
 . clean       remove intermediate files, core files, backup files
 . spotless    clean + remove all dependency files

