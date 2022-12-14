# sinbuger
<div align="center"><img src=".github/logo.png" alt="logo" height="150" width="150"/></div>
<p align="center">A lightweight debugger written in C++</p>

# Why this project?
This project is written based on the tutorial _[Writing a Linux Debugger](https://blog.tartanllama.xyz/writing-a-linux-debugger-setup/)_, the main purpose is to learn the internals of the debugger. The source code of this project will be as clear as possible and given complete but not verbose comments.

# Build
This project is built with gcc 11.2.0. Although it is developed using the C++20 standard, it does not use the features of C++20, so older compiler versions should also be able to build smoothly.

**Recommended toolchain**
- GCC 11.2.0 or newer
- CMake 3.0.0 or newer

# Acknowledge
- _[CLion](https://www.jetbrains.com/clion/)_ is a cross-platform IDE for C and C++, Special thanks to _[JetBrains](https://www.jetbrains.com)_ for licensing free IDEs such as CLion for open source projects.
- The tutorial _[Writing a Linux Debugger](https://blog.tartanllama.xyz/writing-a-linux-debugger-setup/)_ was the main inspiration for this project, Many thanks to _[Sy Brand](https://blog.tartanllama.xyz/)_ for such a great tutorial.

# License
Copyright (c) 2022 Muqiu Han

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM,
DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE
OR OTHER DEALINGS IN THE SOFTWARE.