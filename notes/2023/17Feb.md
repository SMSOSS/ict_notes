# ICT Lesson, 17 Feb Notes #

### 0. Messy Notes ###
- Portability in Programming Languages
  - Can it be ran across different platforms (e.g. Windows, Linux and Mac)
    - High-Level Programming Languages does NOT mean more portable
  - Can be affected by variations of CPU, platform, and much more
    - Different CPU can have different instruction HEX sets
      - e.g. `00000001` may mean "ADD" on a CPU but may mean something else on another CPU

- Object-Oriented Programming VS Procedural Programming
  - Support Polymorphism
  - Support Inheritance
  - Just recite the 4 key difference

- Considerations when choosing a Programming Language
  - Features 
  - Readability
  - Portability
  - Time Efficiency
  - Availibility

### 1. Program Translator ###
- Consists of 2 parts
- Compiler & Interpreter
- Program → Source Code → Compiler → Assembly Language → Assembler → Object Code → Linker → Executable
  - Object Code = Machine Code
  - Linker = Add Shared Libraries and Standard Libraries (Program Libaries) into your code
    - Shared Libraries (e.g. `.dll` in Windows) are libraries provided by System
    - Standard Libaries (e.g. `stdin.h` in C) are libraries provided by Programming Language
- Optimization happens in the process
  - Optimization kills off dumb stuff in code and make your code run faster using smart ways
  
- What happens after translation, when the executable is ran?
  - Executable → Loader → RAM (Main Memory) → CPU
    - Loader loads Executable into main memory for CPU to execute

### 2. Compiler ###
- The thing that translates the 3rd Generation code into machine code (e.g. C++ → HEX ASM)
- Will study the whole code and then remove useless stuff (Optimzation)
- Examples: C++

### 3. Interpreter ###
- Do line-by-line translation, read line and convert that line into machine code.
- Cannot do optimzation as it does not study the whole code. (Main reason why non-compiled languages are slow)
- Good for debugging as can directly show what is wrong and where does the code go wrong
  - Hence C++ has its own interpreter for programmers to debug 
    - Breakpoint = Pause code at breakpoint and allow programmer to view values of variables
    - Step = Run one line and pause, allow programmer to see if anything go wrong at that line
- Examples: PHP and Python
