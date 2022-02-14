# ICT Lesson, Feb 14 Notes #

## 0. Quick Recap ##
- Major compoments in CPU?
    - CU
    - ALU
        - Arthimetic and Logic unit
        - Does all the logic stuff (calculations)
    - Register
        - Lots of different kinds
        - Sort of temporary Memory for CPU

## 1. More CPU stuff ##
- Goes to motherboard

- Motherboard includes
    - extension slots (for hardware like GPU)
    - RAM slots
    - CPU slot (slot?)

- CPU registers
    - Memory != storage
    - It's fast, but it's small
    - Second stage (slowest but large) -> Main Memory (RAM) -> Registers
    - Different Kinds of Registers
        -  General Purpose Register
            - Used for General Storage
            - Just general stuff (store stuff normally)
        - Instrcution Register
            - Used to store instructions to be executed
            - (+-x/)
            - Runs right now (at this moment)
            - Stores Assembly code
            - e.g. ADD BX, CX
            - `ADD` is stored in Instruction register, and `BX` `CX` is stored in General Purpose register.
            - e.g. STORE AX, 15
            - Store 15 to value `AX`
            - Inside the CPU, everything is actually numbers
        - Program Counter
            - Holds (RAM) address of next instruction
        - Memory Address register
            - Holds (RAM) address of data to be processed
        - Memory Data register
            - Holds (RAM) address of data taken / data to be written
        - Status Register
            - Holds status of the command (e.g. is 0? is positive / negative?)

- Transfer of data
    - System Bus
        - Sort of a connector to connect to all compoments
        - Larger bus = Higher processing power
        
        - Data bus
            - Transfers data
        - Address bus
            - Transfers (RAM) addresses
        - Control bus
            - Controllers
        

- Machine cycle
    - Flow of actions in CPU
    - Fetch -> Decode -> Execute
        - Fetch: Take out an instruction to process
        - Decode: Translate to CPU-readable 0 and 1s
        - Execute: Complete the instruction
        - Goes back to "fetch" and takes another instruction

- CPU on some websites
    - Intel:
        - [BRAND] [MODEL] [CLOCK RATE (GHz)]
            - Clock Rate != Speed. Higher clock rate doesn't matter to higher speed
            - Number of clock cycles in 1 second
            - Threads = Jobs it can run at the same time
