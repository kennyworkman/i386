NASM
===

An assembler for 80x86 and x86-64 processors.
Outputs a variety of object file formats but will focus on ELF.

## History of processors

"80-x86" refers to pre-64 bit extensions of x86 architecture:

1978 Intel 8086 16 bit
1982 Intel 80286 24 bit
1985 Intel 80386 32 bit
1989 Intel 80486
1993 Intel Pentium (play on 80586)

x86-64 refers to the 64 bit extension introduced in
2003 AMD Opteron
2004 by Intel

This is not the first 64 bit cpu architecture
(IA-64)

#### Why AMD was first to market

Intel initially partnered with HP to design a non backward compatible 64 bit
architecture designed from scratch called IA-64 / released in the _Itanium_
processor line.

It was AMD that designed the x86-64 ISA (that was indeed an extension to
Intel's own x86) and Intel that followed AMD in creating chips implementing
that ISA.

It supports a range of object file formats, including Linux and *BSD a.out, ELF, Mach-O, 16-bit and 32-bit .obj (OMF) format, COFF (including its Win32 and Win64 variants.)

Recall assembler translates assembly to machine code. Assembly contains human
readable labels called mnemonics to describe operations

## ELF Format

https://en.wikipedia.org/wiki/Executable_and_Linkable_Format#File_layout

## 
