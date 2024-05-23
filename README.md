[![en](https://img.shields.io/badge/lang-en-green.svg)](README.md)
[![ru](https://img.shields.io/badge/язык-ru-blue.svg)](README.ru.md)

# iProg script and calculator disassembler

iProgDecompiler.py decrypts .ipr and produces an assembly code listing and approximate source code.
Since there is no optimization in the iProg compiler, obtaining the script's source code is quite easy.
Of course, without saving the names of functions and variables.

As a bonus, it allows you to unbind the script from the serial number.

Also supports disassembly of calculators - .cal files

The [examples/compiled](examples/compiled) folder contains several examples of compiled scripts.
Decompiled and restored result in [examples/decompiled](examples/decompiled)

# Commands

`python iProgDecompiler.py filename [--bruteforce] | [-sn серийник [серийник ...]]`

> [!TIP]
> If you encounter `SyntaxError: Non-ASCII character '\xd0' in file iProgDecompiler.py on line 48, but no encoding declared; see http://python.org/dev/peps/pep-0263/ for details`  
> Use the following command instead  


`python3 iProgDecompiler.py filename [--bruteforce] | [-sn серийник [серийник ...]]`