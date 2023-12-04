# vktriangle
Vulkan triangle example as a standalone CMake project.
I expect this to be useful as a C++ Vulkan project template.

Source: https://github.com/KhronosGroup/Vulkan-Tutorial

# Building

```
mkdir build && cd build
cmake ..
make
```

# Running
The program (`vktriangle`) expects compiled shaders to be present in `./shaders/`, so it has to be executed from the root of the source directory:

```
./build/vktriangle
```

