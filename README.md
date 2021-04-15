# project3

3/3 of part of the for course OS and systems programming. 

Kernel Hacking

Used sources:
https://www.youtube.com/watch?v=Hl_t6BEBJko,
https://www.geeksforgeeks.org/xv6-operating-system-adding-a-new-system-call,
https://www.youtube.com/watch?v=vR6z2QGcoo8

Added simply count function to xv6 environment. To test the function you need to open terminal on xv6 folder and use promt make. We strongly recommend you to use qemu (can be installed) to test the function, use promt make qemu. Finally write count on qemu and it tells you how many times thhe system has called count function. 

commands to test the function:

make (inside xv6 folder on terminal)
make qemu (-||-)
count (on qemu terminal) 

folders that we modified/made:

syscall.h
defs.h
user.h
sysproc.c
syscall.c
proc.c
count.c
Makefile
usys.S

Santeri Ruuskanen; Joonas Kukonlehto


