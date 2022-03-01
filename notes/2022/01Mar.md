# March 01, ICT Lesson Notes #

## 1. Secondary Storage ##
    - Has connection between RAM and CPU
        - Secondary storage -> RAM -> CPU
    - Used to store large amount of data (very large)

    - Hard drive
        - How does it work?
            - Platters that stores data in 0/1
                - Platters only rotate one way, not both ways
            - Read/write head that looks like a little triangle
            - Access arm that holds the read-write head in place
            - The disk-like thing spins to allow platters to get read by read/write head
        - Usual speed: 
            - Typical: 5400 RPM (roll per minute)
            - Common in 2022: 7200 RPM
            - High-end: 10800 RPM
        - Since it's spinning always, performance will deteoriate by time
            - The more time you use, the slower it will become
            - Affects whole computer's performance
        - HDD is less durable / less shock resistant
        - Advantages
            - It's super cheap
            - Large storage space
        - Defragmentation
            - Rearranges blocks (of data) to make your HDD faster 
            - Moves platters of same file near to one another

    - SSD (solid-state disk)
        - Two types
            - SATA (5x the speed of HDD)
            - M2 (almost 30x speed of HDD)
        - NO readwrite head NO motor
            - Performance does not deteoriate
            - More durable / more shock resistant
        - It's expensive
        - How does it work?
            - Send address to fetch data (similar like RAM)
            - Defragmentation also applies here but it only moves data blocks instead of platters