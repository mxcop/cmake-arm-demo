# CMake ARM
Cross compilation **test**, from Windows to Linux ARM 64-bit.

## Prerequisites :
* CMake (3.15^) *<[cmake-latest](https://cmake.org/download/)>*
* ARM toolchain *<[aarch64-none-linux-gnu](https://developer.arm.com/downloads/-/arm-gnu-toolchain-downloads)>*

## Building
Generate project files (on Windows)
```sh
~ $ mkdir build
~ $ cd build

~/build $ cmake --toolchain ../toolchains/arm.cmake ..
```

Build project (on Windows)
```sh
~/build $ cmake --build .
```
