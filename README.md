# _Esp32 Audio Streaming_
The project contains the code to stream audio .
## Project
The project **Esp32 Audio Streaming** contains one source file in C language [main.c](main/main.c). The file is located in folder [main](main).

ESP-IDF projects are built using CMake. The project build configuration is contained in `CMakeLists.txt`
files that provide set of directives and instructions describing the project's source files and targets
(executable, library, or both). 

Below is short explanation of remaining files in the project folder.

```
TestHabemus
├─ CMakeLists.txt
├─ .devcontainer
├─ .vscode
├─ README.md
└─ main
   ├─ CMakeLists.txt
   └─ main.c               
```
The project was created based on the template provided by the EspressIf Toolchain by running the command 'idf.py create-project'.
## Hardware
* A development board with ESP32-­WROVER-­E
* A USB cable for Power supply and programming
## Development Environment

To configure the laptop with the required development environment, it is recommended to use VS Code and the Espressif IDF extension. 

Setting up the workspace in VS Code for the current project, requires only the following steps:

* Install the Espressif IDF Extension in VS Code **Espressif IDF**
* Clone the repository `https://github.com/ilyes3/TestHabemus.git`
* Open the repository folder in VS Code
* Launch **ESP-IDF: Add vscode configuration folder** (from Command Palette "ctrl+shift+p")

 the following [ESP-IDF Getting Started Guide](https://idf.espressif.com/) explains how to configure, build and flash the project by using directly the `idf.py` commands.
