# stm32f4 submodule of [mcu-framework](https://github.com/yhsb2k/mcu-framework)

[![build](https://github.com/yhsb2k/stm32f4/workflows/build/badge.svg)](https://github.com/yhsb2k/stm32f4/actions?workflow=build)
[![license](https://img.shields.io/github/license/yhsb2k/stm32f4?color=blue)](https://github.com/yhsb2k/stm32f4/blob/master/LICENSE)

## How to build
```
git clone --recursive https://github.com/yhsb2k/stm32f4.git
cd stm32f4
make
```
**Other targets:**
```
make flash - Upload firmware to the target
make erase - Erase all memory on the target
make reset - Reset the target
make debug - Upload firmware to the target and start the debug session
```

## Requirements
* [GNU Arm Embedded Toolchain](https://developer.arm.com/tools-and-software/open-source-software/developer-tools/gnu-toolchain/gnu-rm/downloads)
* [CMake](https://cmake.org/download)
* [Ninja](https://ninja-build.org)
* [Make](https://winlibs.com)
* For Linux (apt): `apt install cmake ninja-build`
