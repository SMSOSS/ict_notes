# The System Unit of a Computer System #

## Table of Content ## 
<!-- TOC -->

- [The System Unit of a Computer System](#the-system-unit-of-a-computer-system)
    - [Table of Content ##](#table-of-content-)
    - [Source](#source)
    - [Homework](#homework)
    - [Major Compoments in CPU](#major-compoments-in-cpu)
        - [Control Unit CU](#control-unit-cu)
        - [Arithmetic and Logic Unit ALU](#arithmetic-and-logic-unit-alu)
        - [Register](#register)
    - [More CPU stuff](#more-cpu-stuff)
        - [Motherboard](#motherboard)
        - [CPU registers](#cpu-registers)
        - [Transfer of data](#transfer-of-data)
        - [Machine cycle](#machine-cycle)
        - [CPU on some websites](#cpu-on-some-websites)
    - [Clock Rate](#clock-rate)
    - [Word length](#word-length)
    - [Main memory](#main-memory)
        - [RAM](#ram)
        - [ROM](#rom)
        - [Cache Memory within CPU](#cache-memory-within-cpu)

<!-- /TOC -->

## Source ##
| Hardware - CPU |
| :------------------- | 
| [14 February 2022](/notes/2022/14Feb.md)|
| [15 February 2022](/notes/2022/15Feb.md)|

## Homework ##
[google form](https://classroom.google.com/u/1/c/Mzg3ODYwNTYwNDU0/a/NDYyMDA2MjU3OTEx/details)

---

## Major Compoments in CPU ##
### Control Unit (CU) ###
- Keep track of sequence of instructions being processed
- Fetches an instructions from main memory 
- Instructs ALU how to perform an operations 
- Monitors and coordinates I/O operations and system units 

### Arithmetic and Logic Unit (ALU) ###
- Perform arithmetic and logic operations (calculations)

### Register ###
- Sort of memory units inside a CPU 
- Provide storage space for ALU and CU
- Lots of different kinds for different data stored / functions

---

## More CPU stuff ##
### Motherboard ###
- extension slots (for hardware like GPU)
- RAM slots 
- CPU slot

### CPU registers ###
- Memory != storage
- Fast but small
- Second stage (slowest but large) -> Main Memory(RAM) -> Registers
- Different Kinds of Registers 
    1. General Purpose Register 
        - Used for General Storage 
        - Just general stuff (store stuff normally)
        - e.g. `BX` , `CX`

    2. Instruction Register 
        - Stores instructions to be executed / assembly code
        - Runs right now (at this moment)
        - e.g. `ADD`
        - Inside CPU , everything is actually numbers 
    
    3. Program Counter
        - Contains memory address (RAM) of next instruction to be executed
    
    4. Memory Address register
        - Contains memory address (RAM) of data to be processed

    5. Memory Data register 
        - Contains memory addess (RAM) of data taken / to be written

    6. Status register 
        - Contains status of command (e.g. is 0? postive/negative? )  

### Transfer of data ###
- System Bus
    - Sort of a connector to connect to all compoments 
    - larger bus = higher processing power 

    - Data bus (transfers data)
    - Address bus (transfers (RAM) addresses)
    - Control bus (controller)

### Machine cycle ###
- Process of executing an instruction in a CPU (flow of actions in CPU)
- Fetch -> Decode -> Execute
    - Fetch : Take out an instruction to process
    - Decode : Translate to CPU-readable 0 and 1s
    - Execute : Complete the instruction 
    - Goes back to "fetch" and takes another instruction

### CPU on some websites ###
    - Intel :
        - [BRAND] [MODEL] [CLOCK RATE (Ghz)]
            - Clock Rate != Speed (doesn't matter)
            - Number of clock cycles in 1s
            - Threads = Jobs it can run at same time
    - bruh no amd ge sed :(

---

## Clock Rate ##
- 5.1GHz (10^9) = 5100MHz (10^6) = 5100000KHz (10^3)
- Hz = Hertz (frequency)
- Extra: NS and MS
        - NS (nano-second): 10^-9 second
        - MS (micro-seond): 10^-6 second

---

## Word length ##
- A command will be converted to HEX to be passed on to PC
- e.g. `ADD AX , 3`
    - ADD will become `0001`
    - AX will become `0010`
    - 3 will become `0011`
    - The command will be 12-bits
- 64 bits = can store command that's 64bits long
- *Advantages* of larger bits:
    - Can store a larger value (because more bits)
        - Largest value 4 bits is `15` (`1111`)
        - Larger the bits = more it can store / commands it can do / built-in functions (Can do more complicated things easily)

## Main memory ##
- Important compoment
- Hard disk(slow) -> Main Memory -> CPU(fast)

### RAM ###
- RAM can cache stuff -> processing faster
    - e.g. Cache previous calculations 
    - e.g. Cache datasets that will be used in the future 
- CPU don't have enough storage to save stuff -> we need RAM
- RAM = **[temporary]** storage / buffer for data and instructions to be processed by CPU
- **[volatile]** storage 
    - All things in RAM will be cleared once devide is powered off
    - Some PAM will clear data themselves
- RAM measuring unit = Gigabytes (till now)

### ROM ###
- read only memory , uneditable 
- **[Non-volatile]**
- Loads basic tools that's necessary for operation of computer
            - e.g. BIOS
            - e.g. bootstrap program

### Cache Memory (within CPU) ###
- Small stoage 
- High data acess rate 
- Fastest within all main memory
- Usually kept small in storage size due to it being very expensive
