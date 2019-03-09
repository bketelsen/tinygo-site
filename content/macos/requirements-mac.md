---
title: "Requirements - macOS"
weight: 1
---

These are the base requirements and enough for most (desktop) use.

- Go 1.11+
- LLVM 7 (for example, from [apt.llvm.org](http://apt.llvm.org/)

Linking a binary needs an installed C compiler (`cc`). At the moment it
expects GCC or a recent Clang.

## Install Go

## Install LLVM 7

## WebAssembly - Optional

The WebAssembly backend only needs a special linker from the LLVM project:

- LLVM linker (`ld.lld-7`) for linking WebAssembly files together.
