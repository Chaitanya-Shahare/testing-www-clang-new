+++
title = ''
date = 2024-09-29T16:13:03+05:30
draft = false
+++

## Features and Goals

Some of the goals for the project include the following:

### End-User Features:

- Fast compiles and low memory use
- Expressive diagnostics (examples)
- GCC & MSVC compatibility

### Utility and Applications:

- Modular library based architecture
- Support diverse clients (refactoring, static analysis, code generation, etc.)
- Allow tight integration with IDEs
- Use the LLVM 'Apache 2' License

### Internal Design and Implementation:

- A real-world, production quality compiler
- A simple and hackable code base
- A single unified parser for C, Objective C, C++, and Objective C++
- Conformance with C/C++/ObjC and their variants

Of course this is only a rough outline of the goals and features of Clang. To get a true sense of what it is all about, see the Features section, which breaks each of these down and explains them in more detail.

## Why?
Development of the new front-end was started out of a need for a compiler that allows better diagnostics, better integration with IDEs, a license that is compatible with commercial products, and a nimble compiler that is easy to develop and maintain. All of these were motivations for starting work on a new front-end that could meet these needs.

## Current Status

Clang is considered to be a production quality C, Objective-C, C++ and Objective-C++ compiler when targeting any target supported by LLVM. As example, Clang is used in production to build performance-critical software like Chrome or Firefox.

If you are looking for source analysis or source-to-source transformation tools, Clang is probably a great solution for you. Please see the C++ status page or the C status page for more information about what standard modes and features are supported.

## Get it and get involved!

Start by getting the code, building it, and playing with it. This will show you the sorts of things we can do today and will let you have the "Clang experience" first hand: hopefully it will "resonate" with you. :)

Once you've done that, please consider getting involved in the Clang community. The Clang developers include numerous volunteer contributors with a variety of backgrounds. If you're interested in following the development of Clang, signing up for a mailing list is a good way to learn about how the project works.