# ICT lesson, 15 Feb Notes #

## 0. Continuation on Clock Rate ##
    - 5.1GHz (10^9) = 5100MHz (10^6) = 5100000KHz (10^3)
    - Hz = Hertz
    - Extra: NS and MS
        - NS (nano-second): 10^-9 second
        - MS (micro-seond): 10^-6 second

## 1. Word length ##
    - A command will be converted to HEX to be passed on to PC
    - e.g. ADD AX,3
        - ADD will become `0001`
        - AX will become `0010`
        - 3 will become `0011`
        - The command will be 12-bits.
    - 64 bit = can store command that's 64 bits long.
    - ADVANTAGES of larger bits:
        - Can store a larger value (because more bits)
            - Largest value 4 bits can store is `15` (`1111`)
            - The larger the bits, the more it can store
            - The larger the bits, the more commands it can do
            - The larger the bits, the more the built-in functions (Can do more complicated things easily)

## 2. Main memory ##
    - Important compoment
    - Hard disk -> Main Memory -> CPU
    - Main memory is faster than hard disk but slower than CPU
    - RAM can cache stuff, and hence make processing faster
        - e.g. Cache previous calculations
        - e.g. Cache datasets that will be used in the future
    - CPU don't have enough storage to save stuff, and that's why we need RAM
    - RAM = **[temporary]** storage / buffer for data and instructions to be processed by CPU
    - RAM = **[volatile]** storage.
        - All things in RAM will be cleared once device is powered off.
        - Some RAM will clear data themselves
    - RAM measuring unit = Gigabytes (till now)

    - ROM = read only memory
        - Read-only, uneditable
        - Non-volatile
        - Loads basic tools that's necessary for operation of computer
            - e.g. BIOS
            - e.g. bootstrap program
    
    - Cache Memory (within CPU)
        - Small storage
        - High data access rate
        - Fastest within all main memory
        - Usually kept small in storage size due to it being very expensive
    
    