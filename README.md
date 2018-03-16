# Backchannels

When people communicate, listeners produce non-verbal responses to the speaker. These responses are crucial for successful communication. The academic name for this responses is backchannels.

This repo provide a set of backchannel models that are based on the speaker prosody (without assuming anything about the content). They are implemented in [Pure Data](https://puredata.info/).

Start from `models_tester.pd` and continue from there.

## Compiling externals

The Pd externals are already complied and checked into the repo. If you want to recompile them.

First:

    git submodule init
    git submodule update

### Linux

    make
    
### Windows

1. Install [MSYS2](https://www.msys2.org/).
1. Open MSYS2 MinGW 32-bit.
1. Install the development tools with `pacman -S mingw-w64-i686-toolchain mingw-w64-i686-clang make`.
1. `make`
