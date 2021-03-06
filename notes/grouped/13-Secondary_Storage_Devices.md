# Secondary Storage Devices #

## Table of Content ##
<!-- TOC -->

- [Secondary Storage Devices](#secondary-storage-devices)
    - [Table of Content](#table-of-content)
    - [Source](#source)
    - [Secondary Storage](#secondary-storage)
        - [Hard Drive](#hard-drive)
        - [SSD solid-state disk](#ssd-solid-state-disk)
    - [Portable Storage Devices](#portable-storage-devices)
        - [USB Universial Serial Bus Flash Drives](#usb-universial-serial-bus-flash-drives)
        - [Cloud Storage](#cloud-storage)
        - [SD Cards](#sd-cards)
        - [DVD / Blu-Ray DVD](#dvd--blu-ray-dvd)
        - [Cassette Tape](#cassette-tape)
        - [Video Cassette](#video-cassette)
        - [Network Storage](#network-storage)

<!-- /TOC -->

## Source ##
| Hardware - Storage devices |
| :------------------- | 
| [1 March 2022](/notes/2022/01Mar.md)|
| [2 March 2022](/notes/2022/02Mar.md)|
| [9 March 2022](/notes/2022/09Mar.md)|

## Secondary Storage ##
- Has connection between RAM adn CPU 
    - Secondary storage -> RAM -> CPU 
- Used to store large amount of data (very large)

### Hard Drive ###
- How does it work? 
    - Platters that stores data in 0/1  (Binary Style)
        - Platters only rotate one way , not both ways
    - Read/write hand that looks like a little triangle 
    - Access arm that holds the read-write head in place 
    - The disk like things spins to sllow platters to get read by read/write head
- Usual speed:
    - Typical : 5400 RPM (roll per minute)
    - Common in 2022 : 7200 RPM
    - High-end : 10800 RPM
- Since it's spinning always , performance will deteoriate by time 
    - More time you use = slower 
    - Affects whole computer's performace 
        - More significant if your OS installation is on the HDD
- HDD is less durable / less shock resistant 
- Advantages :
    - Super cheap 
    - Large storage space
- Defragmentation 
    - Rearrange blocks (of data) to make yout HDD faster 
    - Move platters of same file near to one another for faster read speed (no need to spin too much for a file)

### SSD (solid-state disk) ###
- Two types 
    - SATA (5x the speed of HDD)
    - M2 (almost 30x speed of HDD)
- How does it work ? 
    - Send address to fetch data (similar to RAM)
    - Defragmentation also applies here but it only move data blocks instead of platters 
- No readwrite head & No motor 
    - Performance does not deteoriate
    - More durable / more shock resistant
- It's expensive

## Portable Storage Devices ##
### USB (Universial Serial Bus) Flash Drives ###
- Occupies physical space -> possibly be lost / damaged 
- Speed / Time needed varies by USB port 
    - USB 2 is slower than USB 3 (Newer Standard)

### Cloud Storage ###
- e.g. Google Drive , OneDrive / Skydrive / Dropbox
- Requires (stable) internet connection 
- Good security (Hackers can still steal data if they want tho...)
- (Usually) larger storage
- Cheaper than others in general 

### SD Cards ###
- For smaller devices (e.g. Cameras (SD) and Mobile Phones (Mirco SD) )
- Storage capacity and price is similar to USB flash drive 

### DVD / Blu-Ray DVD ###
- Physically larger (looks like a disk)
- Smaller capacity (DVD 4 GB / Blu-ray DVD 20GB)
- Cheap 
- Used to store movies (usually)

### Cassette Tape ###
- For listen music / store audio 
- Need wait to let it rotate to specific song 
- You can also rotate to make it play a specic song 

### Video Cassette ###
- Basically same as audio casette but for video 

### Network Storage ##
- Network storage != cloud storage 
- e.g. NAS (Network Attached Storage)
- Shared among WiFi connection -> Network required
- Expandability (insert hard disk to increase storage)
- Has advanced backup system (some of them)
- NAS -> for small office / family 
- SAN storage -> for larger data 