# AVR(ATmega32) Project Template (for VS Code)

This is a basic AVR project setup using `make` and `avr-gcc`, designed for use with **Visual Studio Code** on Windows.  
It automatically compiles all `.c` files (inside src).
---

### 📁 Folder Structure
├── .vscode

│ ├── c_cpp_properties.json

├── Makefile

├── src

├── inc

│ ├── main.c

│ ├── MCAL

│ └── HAL

├── build ← created automatically during build

├── main.elf ← compiled ELF file

├── main.hex ← hex file for flashing
---

### ⚙️ VS Code Setup

> Create a .vscode folder in the project root and move c_cpp_properties.json into it.

> Move MakeFile to project root

---
### 🛠 Build the Project

In VS Code terminal or PowerShell:

```sh
make
```

---
### 🔄 Clean the Build
```sh
make clean
```
This removes all .o, .d, .elf, and .hex files.
---
### 💡 Notes
You can add more .c files anywhere inside src/

No need to edit the Makefile


It automatically recompiles files if a header file changes

