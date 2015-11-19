# Toolchains

This project, available from [GitHub](https://github.com/xpacks),
includes the definitions of many GCC & Clang toolchains.

Each toolchain has two versions, one for debug and one for release configurations.

Most of the Linaro (32/64-bits) and Bare-metal toolchains are supported.

Native OS X toolchains include Apple Clang and multiple MacPorts GCC versions.

The currently supported toolchains are:

## GCC

* ilg/toolchain/gcc/arm-none-eabi/debug (/release)
* ilg/toolchain/gcc/linaro/armv7/arm-none-eabi/debug (/release)
* ilg/toolchain/gcc/linaro/armv7/armeb-none-eabi/debug (/release)
* ilg/toolchain/gcc/linaro/armv7/arm-linux-gnueabihf/debug (/release)
* ilg/toolchain/gcc/linaro/armv7/armeb-linux-gnueabihf/debug (/release)
* ilg/toolchain/gcc/linaro/aarch64/aarch64-none-elf/debug (/release)
* ilg/toolchain/gcc/linaro/aarch64/aarch64\_be-none-elf/debug (/release)
* ilg/toolchain/gcc/linaro/aarch64/aarch64-linux-gnu/debug (/release)
* ilg/toolchain/gcc/linaro/aarch64/aarch64\_be-linux-gnu/debug (/release)
* ilg/toolchain/gcc/mp/4.9/32/debug (/release)
* ilg/toolchain/gcc/mp/4.9/64/debug (/release)
* ilg/toolchain/gcc/mp/5/32/debug (/release)
* ilg/toolchain/gcc/mp/5/64/debug (/release)

## Clang

* ilg/toolchain/clang/osx/32/debug (/release)
* ilg/toolchain/clang/osx/64/debug (/release)

## To be added

* GNU/Linux 32/64-bits toolchains
* GNU/Linux 32/64-bits Clang
* Mingw-w64 32/64-bits toolchains

