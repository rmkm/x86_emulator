# x86_emulator

## Descrition
x86 CPU emulator written in C.

## Requirement
gcc

## Usage
Generate binary file as input of x86 emulator.
```
nasm sample.asm -o sample.bin
```
Compile x86 emulator. This will generate `x86_emulator`
```
make
```
Run x86_emulator.
```
./x86_emulator sample.bin
```
