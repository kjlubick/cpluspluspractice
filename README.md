# Practice grounds for C++

## Generate Buildfiles

    cmake -GNinja

## Build all executables

    ninja


## Compiler
I'm using clang 4.0 for builds - no guarantees of other ones working.


## Cleanup
The following will remove all build files and extra stuff.

    git clean -xf
    git clean -df