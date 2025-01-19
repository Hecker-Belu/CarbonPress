# CarbonPress
A compiler for my custom language (Carbon)

# Requirements
gcc
nasm
OS: Windows x64

# Carbon Language
Carbon is stack based

PUSH Int ; Push an integer to the stack
POP ; Pop from stack
ADD ; add the last 2 stack values
SUB ; same as add
PRINT String Literal ; Prints out a string literal
READ ; reads user input (integer)
JE Label ; Jumps to a label if 0 flag (Stack Pointer value = 0)
JGT Label ; jumps if greater than
Label: ; creates a label
HALT ; Finish program
