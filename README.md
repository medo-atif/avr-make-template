# AVR Project Template (for VS Code)

This is a basic AVR project setup using `make` and `avr-gcc`, designed for use with **Visual Studio Code** on Windows.  
It automatically compiles all `.c` files (inside src).
---

## 📁 Folder Structure
├── Makefile

├── src

├── inc

│ ├── main.c

│ ├── MCAL

│ └── HAL

├── build ← created automatically during build

├── main.elf ← compiled ELF file

├── main.hex ← hex file for flashing

##💡 Notes
You can add more .c or .h files anywhere inside src/

No need to edit the Makefile

It automatically recompiles files if a header file changes
