# FLOSS test: test-decode-to-stack

Purpose: Demonstrate extraction of strings decoded to the stack.
Decoding algorithm: single byte xor
Input buffer location: stack
Output buffer location: stack

Decoded strings:
hello world

Source files:
test-decode-to-stack.c

Build instructions (Windows):
eg. cl.exe test-decode-to-stack.c /Fetest-decode-to-stack.exe

Build instructions (Linux):
eg. clang test-decode-to-stack.c -o test-decode-to-stack

Build instructions (Cross compile for Windows on Linux):
i686-w64-mingw32-clang test-decode-to-stack.c -o test-decode-to-stack.exe