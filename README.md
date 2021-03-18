# Pre-built GNU Cross Toolchain for Mac

Target platform: `x86_64-unknown-linux-gnu`.

Built with toolchain-NG. Intended for Mac users who want to build on Mac and run on Linux.

    Languages       : C,C++
    OS              : linux-4.20.8
    Binutils        : binutils-2.32
    Compiler        : gcc-8.3.0
    C library       : glibc-2.29
    Debug tools     : gdb-8.2.1
    Companion libs  : expat-2.2.6 gettext-0.19.8.1 gmp-6.1.2 isl-0.20 libiconv-1.15 mpc-1.1.0 mpfr-4.0.2 ncurses-6.1 zlib-1.2.11


For Rust:
```
export CARGO_TARGET_X86_64_UNKNOWN_LINUX_GNU_LINKER=path/to/unpacked_toolchain/x86_64-unknown-linux-gnu/bin/x86_64-unknown-linux-gnu-gcc
export CC=path/to/unpacked_toolchain/x86_64-unknown-linux-gnu/bin/x86_64-unknown-linux-gnu-gcc
```
