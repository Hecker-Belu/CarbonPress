# CarbonPress
A compiler for my custom language (Carbon)

# Requirements
gcc\n
nasm\n
OS: Windows x64\n

# Carbon Language
Carbon is stack based\n

PUSH Int ; Push an integer to the stack\n
POP ; Pop from stack\n
ADD ; add the last 2 stack values\n
SUB ; same as add\n
PRINT String Literal ; Prints out a string literal\n
READ ; reads user input (integer)\n
JE Label ; Jumps to a label if 0 flag (Stack Pointer value = 0)\n
JGT Label ; jumps if greater than\n
Label: ; creates a label\n
HALT ; Finish program\n
