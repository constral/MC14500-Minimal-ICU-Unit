# MC14500 Minimal ICU Unit

<image src="picture.jpg" width="800px"/>

This project involved the physical implementation of the "Minimal ICU Unit" system described in the Motorola MC14500 logic processor handbook, using modern hardware equivalents on breadboards. This involved dealing with several digital system components, including a clock system, program memory, and I/O interfacing. The hands-on implementation gave me a deeper understanding of how digital systems as well as their components operate.

## Overview
On the software side, programming can be done manually via DIP switches and assembly code added inside the program memory, but it can also be performed via electrical signals sent from an Arduino development board. Eventually, several software implements were created to aid with programming the computer, such as the C++ assembler for writing binary code to the memory of the computer, as well as a Python script that compiles the code to be forwarded to the assembler. Seeing as the MC14500 only contains a logic unit, it is only possible for it to perform arithmetic operations via emulating the logic gates of an arithmetic unit by code; I also explored this aspect of the machine, by implementing algorithms that used logic functions to perform addition and multiplication.
<image src="original_schematic.jpg" width="600px"/>