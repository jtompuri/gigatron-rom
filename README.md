Software for Gigatron ROM
=========================

Files
=====
```
theloop.py                      Video/audio/io/interpreter loops
                                Built-in vCPU applications
                                Execute to update ROM files
gcl.txt                         Gigatron Control Language explanation
gtemu.c                         Emulator / executable instruction set definition
LICENSE                         2-Clause BSD License
Makefile                        Marcel's Makefile
```

Files processed by theloop.py
=============================
```
main.gcl                        Application code
gcl.py                          Module: GCL to vCPU compiler
asm.py                          Module: Assembler functions
font.py                         Module: Gigatron font definition
Images/Parrot-160x120.rgb       Raw RGB image file (source: Parrot-160x120.png)
Images/Jupiter-160x120.rgb      Raw RGB image file (source: Jupiter-160x120.png)
```

Files generated by theloop.py
=============================
```
theloop.asm                     Annotated disassembly, with labels and comments
theloop.0.rom                   ROM file for 28C256 #0 (breadboard)
theloop.1.rom                   ROM file for 28C256 #1 (breadboard)
theloop.2.rom                   ROM file for 27C1024 (PCB versions)
```