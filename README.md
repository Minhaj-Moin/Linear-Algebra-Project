# Linear-Algebra-Project
Application of Concepts of Parallel Projection and Rotation Matrices that I learnt in my Linear Algebra Course taken in the fifth semester of my Bachelors at Habib University.

## Compiling
This uses and has been tested only on MinGW. Make relevant changes to the Makefile to include your SDL Libraries, then type '''mingw32-make.exe''' to compile.

## Current Issues
* Euler Angles have been used for rotations which are resulting in undesired transformations
* OBJ file parser requires faces to not have '/' in the file.
