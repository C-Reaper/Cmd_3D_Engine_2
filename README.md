## Overview
This project is a simple 3D engine implemented in C. It uses basic rendering techniques to display a rotating cube on the screen.

## Features
- Basic 3D rotation of a cube.
- Wireframe rendering of the cube.
- No user interaction or input handling.
- No advanced lighting or shading.

## Project Structure
```
Cmd_3D_Engine_2/
├── build/
├── src/
│   ├── Main.c
│   └── Console.h
├── Makefile.linux
├── Makefile.windows
├── Makefile.wine
└── README.md
```

### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility

## Build & Run
To build the project on Linux:
```sh
cd Cmd_3D_Engine_2
make -f Makefile.linux all
make -f Makefile.linux exe
```

To clean and rebuild the project:
```sh
make -f Makefile.linux clean
make -f Makefile.linux all
```

To build the project on Windows:
```sh
cd Cmd_3D_Engine_2
make -f Makefile.windows all
make -f Makefile.windows exe
```

To run the executable:
```sh
./build/Main.exe
```

For Emscripten or WebAssembly, use the provided Makefile.web and follow similar steps.