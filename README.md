# C++ 20 Concept Based DI Example

This example has been tested with MacOS 11.3+.

## Prerequisites

1. `CMAKE` in the path `/Applications/CMake.app/Contents/bin/cmake`
2. G++ compiler, `brew install gcc`

## How to build

1. `mkdir build`
2. `cd build`
3. `cmake ..`
4. `make -j12`

## How to run

1. `cd build`
2. `./concept_based_di`

Output:

```sh
❯ ./concept_based_di
[INFO]Hello Logger DI: all
[INFO]Hello Logger DI: two
[INFO]Hello Logger DI: onlyLogger
```
