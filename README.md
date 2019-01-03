# avr-projects
Atmel AVR microcontroller projects. (Primarily Arduino-based)

AVR Overview (https://hackaday.com/2010/10/23/avr-programming-introduction/)

*How to use*: 
On Mac (OSX 10.6 and newer)--AVR Toolchain (https://www.obdev.at/products/crosspack/index.html)
On Linux--GCC-AVR and avrdude
```
sudo apt update
sudo apt upgrade all
sudo apt-get install gcc-avr binutils-avr avr-libc
sudo apt-get install gdb-avr
sudo apt-get install avrdude
```

On Windows--WinAVR (https://sourceforge.net/projects/winavr/)

*Building with Arduino*:
1. Make a subdirectory for each project (easiest if you copy the Makefile and edit it for each project). Likely will only need to change top 5 lines.
2. Compile the .c program
`make`
3. Download compiled code to AVR board
`make flash`
