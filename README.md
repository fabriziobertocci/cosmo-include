# cosmo-include
A set of very empty header files that can be used when building apps with Cosmopolitan

## Why?
When you build an application with [Cosmopolitan](https://github.com/jart/cosmopolitan), you only need one header file (`cosmopolitan.h`). 
If your (existing) code already have a bunch of system `#include`, you are going to get all those pesky 'No such file or directory'.

## Solution
Check out this tree of empty files and add `-I<this directory>` to the gcc command line.

## Note
The list of files is not complete... Just keep adding empty files matching the header your code is trying to include
