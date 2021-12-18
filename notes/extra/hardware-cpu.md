# Hardware Extras (CPU)#

- Types of hardware
    - CPU
    - RAM
    - I/O Devices
    - Secondary storage

- CPU
     - Reference to book is "highly" recommended
    - Includes AU, CU and registers
        - ALU = Arithmetic & Logic Unit
             - Deals with the calculation part +  and or not
             - Can only do addition and read the and or nots
             - worse than a calculator
        - CU = Control unit
              - NOT calculation, not and or not
        - Registers (stores data)
              - General Purpose register 
              - Control Register (saves instructions that will run soon)
             - Instruction register (saves running instructions)
             - Memory Address Register (saves what offset is the data at in RAM)
             - Memory Data Register (saves the data pulled from offset in RAM)
             - Status Register (saves result of command)
             - Program counter (saves next command)
    - CPU runs assembly code (ezpz)
         - assembly code become machine code and CPU run it
         - armconverter.com is your friend :) (armv7 and armv8 only)

    - CPU rundown
            - fetch -> decode -> execute -> repeat
    - clock rate
           - measurement unit: (G/M)Hz 
               - G = 10⁹ (×1000 not ×1024. It is not a storage unit )

           - How many times it can 通電 and 斷電 every second
           - Clock rate high ≠ processing speed fast

    - Word length
           - 32bit / 64bit 
           - how long string can a bit store
           - more bit = more function
