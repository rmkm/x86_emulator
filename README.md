# x86_emulator

## Descrition
x86 CPU emulator written in C.

## Requirement
gcc  
objdump

## Usage

### x86 emulator
Generate binary file as input of x86 emulator
```
nasm sample/asm/sample.asm -o sample/asm/sample.bin
```
Compile x86 emulator. This will generate `x86_emulator`.
```
make
```
Run x86_emulator
```
./x86_emulator sample/asm/sample.bin
```

### Disassemble
Generate object file
```
cd sample/disassemble/
gcc -c -g -o main.o main.c
```
Disassemble the object file
```
objdump -d -S -M intel main.o
```
