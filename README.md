# Chip-8 Disassembler and Emulator written in 32-bit x86 assembly.

## Compiling on WSL for win32

nasm -f win32 src/winapi_io.asm -o build/accumulate.obj && i686-w64-mingw32-gcc build/accumulate.obj -o main.exe && rm build/accumulate.obj 

