# xo projects

A set of libraries for complex event processing

## Features

- native c++
- deterministic simulation
- reflection
- python bindings

## Getting Started

### build + install
```
$ cd xo
$ mkdir build
$ cd build
$ PREFIX=/usr/local # for example
$ cmake -DCMAKE_INSTALL_PREFIX=${PREFIX} ..
$ make -j
$ make install
```

### LSP support
```
$ cd xo-ordinaltree
$ ln -s build/compile_commands.json   # since lsp looks for compile_commands.json in root of source tree
```
