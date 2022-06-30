# Secondary Storage Devices #

## Table of Content ##

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
    - Platters that sotres data in 0/1 
        - Platters only rotate on way , not both ways
    - Read/write hard that looks like a little triangle 
    - Access arm that holds the read-write head in place 
    - The disk like things spins to sllow platters to get read by read/write head
- Usual speed:
    - Typical : 5400 RPM (roll per minute)
    - Common in 2022 : 7200 RPM
    - High-end : 10800 RPM
- Since it's spinning always , performance will deteoriate by time 
    - More time you use = slower 
    - Affects whole computer's performace 
- HDD is less durable / less shock resisteant 
- Advantages :
    - Super cheap 
    - Large storage space
- Defragmentation 
    - Rearrange blocks (of data) to make yout HDD faster 
    - Move platters of same file near to one another 

### SSD (solid-state disk) ###
- Two types 
    - SATA (5x the speed of HDD)
    - M2 (almost 30x speed of HDD)
- How does it work ? 
    - Send address to fetch data (similar to RAM)
    - Defragmentation also applies here but it only move data blocks instead of platters 
- No readwrite head No motor 
    - Performance does not deteoriate
    - More durable / more shock resistant
- It's expensive

## Portable Storage Devices ##
### USB (Universial Serial Bus) Flash Drives ###
- Occupies physical space -> possibly be lost / damaged 
- Speed / Time needed varies by USB port 
    - USB 2 is slower than USB 3

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
- e.g. NAS (Netwoek Attached Storage)
- Shared among WiFi connection -> Netwoek required
- Expandability (insert hard disk to increase storage)
- Has advanced backup system (some of them)
- NAS -> for small office / family 
- SAN storage -> for larger data 