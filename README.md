# STM32-vscode-template
A template for STM32 development with vscode

## Resources
 - [Matej Blagšič's youtube channel](https://www.youtube.com/watch?v=FkqQpBqkSns)

## Pre-requirements
  - [CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html)
  - [Cortex-debug (vscode extension)](https://github.com/Marus/cortex-debug)
  - [Makefile Tools (vscode extension)](https://github.com/microsoft/vscode-makefile-tools)
  - [C/C++ (vscode extension)](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools) 
  - [C/C++ Extension Pack (vscode extension)](https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack) 
  - [gcc arm none eabi](https://developer.arm.com/downloads/-/gnu-rm)
  - [Cmake](https://cmake.org/)


## Setting up the environment
  some info here 


## Creating a new STM32 project
  1. Create a new CubeMX project 
      - Select the target MCU
      - Config clocks and peripherals as needed
      - In "Project Manager":
        - In "Project" select "Toolchain / IDE: Makefile"
        - In "Code Generator" tick "Copy only the necessary library files" 
        - In "Advanced Settings" select "LL" instead of "HAL" in Driver Selector
