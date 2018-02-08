# LLVM

A clone of [LLVM](https://llvm.org/) 3.9.1 modified for use in [RetDec](https://github.com/avast-tl/retdec) and associated tools.

**Warning: LLVM in this repository was modified and does not behave the same as the vanilla version!**

## License

Copyright (c) 2003-2016 University of Illinois at Urbana-Champaign. Licensed under the University of Illinois/NCSA Open Source License. See the `src/LICENSE.txt` file for more details.

## Contributing

In order to improve the decompilation quality, it is sometimes needed to modify LLVM libraries used by the RetDec decompiler. Any such modification must be consulted with RetDec developers. All modifications must be delimited and marked with keywords `RetDec` or `decompiler` so that it is possible to migrate them to new LLVM sources when the LLVM version is upgraded. When modifying LLVM source code, use the same coding conventions as LLVM uses.
