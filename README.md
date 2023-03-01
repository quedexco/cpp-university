# C++ University

Modern C++ CMake project for self-learning.

## To-Build

Initialise CMake build:

```bash
rm -rf build
cmake -S . -B build
```

Build project:

```bash
cmake --build build --target all -j 9
```

Run unit tests:

```bash
cd build && ctest
```

