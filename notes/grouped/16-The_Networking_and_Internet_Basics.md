# The Networking and Internet Basics #

## Table of Content ##
<!-- TOC -->

- [The Networking and Internet Basics](#the-networking-and-internet-Basics)
    - [Table of Content](#table-of-content)
    - [Source](#source)
    - [Network ##](#network-)
        - [LAN Local Area Network](#lan-local-area-network)
        - [WAN Wide Aread Network](#wan-wide-aread-network)
    - [Network Services](#network-services)
        - [Internet Communication](#internet-communication)
        - [Hardware Sharing](#hardware-sharing)
        - [Centralized Data Management P.185](#centralized-data-management-p185)
        - [Software Sharing](#software-sharing)
        - [Internet Access Service Sharing](#internet-access-service-sharing)
        - [Network Conferencing](#network-conferencing)
        - [Information Backup](#information-backup)
    - [Network Equipments](#network-equipments)
        - [Network Interface Card P.190](#network-interface-card-p190)
        - [Twisted-pair Cable P.196](#twisted-pair-cable-p196)
        - [Router P.193](#router-p193)
        - [Switch](#switch)
    - [Repeater](#repeater)
        - [Modem](#modem)
        - [Access Point](#access-point)
    - [Connections](#connections)
        - [Wireless](#wireless)
        - [Wired](#wired)
        - [Comparision](#comparision)
    - [WiFi](#wifi)
        - [SSID](#ssid)
        - [Key](#key)
        - [Frequency](#frequency)
        - [T-carrier P.205](#t-carrier-p205)

<!-- /TOC -->

## Source ##
| Networking |
| :------------------- | 
| [4 May 2022](/notes/2022/04May.md) - Basics & LAN |
| [5 May 2022](/notes/2022/05May.md) - Uses of networks |
| [11 May 2022](/notes/2022/11May.md) - Network Equipments |
| [18 May 2022](/notes/2022/18May.md) - Network Equipments (cont.) and Connections |
| [23 May 2022](/notes/2022/23May.md) - Introduction to WiFi |

---

## Network ## 
- Biggest network = Internet 
- Electronic Devices making connection (e.g. voice chat)

### LAN (Local Area Network) ###
- Types of LANS :
    - Peer-to-peer (All are equal , no server)
    - Client-server (Connect to a central server/ host computer , e.g. discord server)

### WAN (Wide Aread Network) ###
- Communications network spans a large geographical area

---

## Network Services ##
### Internet Communication ###
- e.g. Whatsapp , Telegram , Instagram 

### Hardware Sharing ###
- Share hardware resources (e.g. printers)
- PCs connected to server , server connected to printer 

### Centralized Data Management (P.185) ###
- Latest and identical information can be shared to all authorized users all the time 
- Allow many users to work on same prject at the same time -> Increase productivity
- Manage multi devices at the same time (e.g. Install programs for all devices)

### Software Sharing ###
- Install software quickly for multi devices 
- Save money and install time 

### Internet Access Service Sharing ###
- User can access the Internet via computer netwoek with a single Internet service account 
- Reducing cost of Internet access , helping monitor/control/protect network communication 

### Network Conferencing ###
- Enable users in two or more locations to communicate with each other via two-way audio and video siganls 
- e.g. Google meet , Zoom , etc.

### Information Backup ###
- Information on individual computers can be backed up and stored on server via network 

---

## Network Equipments ##

### Network Interface Card (P.190) ###
- Important for going online (Connecting computer to network)
- Allow LAN cable to be inserted to PC (hardware part that goes to the motherboard)

### Twisted-pair Cable (P.196) ###
- Network cables 
- Winding two conductors together -> eliminate electromagnetic interference
- Types of twisted-pair cables:
    - Shielded twisted-pair (STP)
        - Has metal wrapper to reduce noise and electromagnetic interference
    - Unshielded twisted cable (WTP)

### Router (P.193) ###
- Connetion between differents LANS 
- Groups all LANs into one
- Have function of switch

### Switch ###
- Central connection point for cables on a network 
- Connect one or more computers 

## Repeater ###
- Amplifies received siganls -> extend the coverage of network 
- Overcome the problem of poor signal due to long distance transmission

### Modem ###
- Modem = Modulator - Demodulator
- PC to Router signal != Modem to internet signal 
- Translate analog to digital signal & digit to analog signal 
- PC -> Switch -> Router -> Modem -> Internet
- Transfer by 0 and 1
- Extra: Router is not really needed
    - Since router groups all LANs into one, if you only have 1 LAN device you can use Switch only and skip Router.

### Access Point ###
- For Wireless Connection (WiFi)
- WLAN (Wireless Local Area Netwoek) can be connected to a wired LAN
- Allow wireless device to communicate to other wireless or wired network

---

## Connections ##
### Wireless ###
1. Satellite 
    - Send data to stellite via satellite dish
2. Microwave 
    - Send and receive radio signals 
3. WiFi Connections 
    - Wireless Fidelity 
    - Transmitted by radio waves
4. Infrared
5. Bluetooth

### Wired ###
1. Optical Fiber
    - Transfer data by ligh and reflection with glass
    - Super fast 
    - Super expensive (extra equipment is needed)
    - Mouse can bite the cable 
2. Coaxial Cable
    - Cable TV connections
3. Twisted Pair (STP / UTP , CAT1 - CAT7)
    - Cheaper 
    - Reasonable speed
    - Easy to set up

### Comparision ###
| Method (Wired / Wireless)                 | Cost                 | Speed | Security | Portability |
| :------------------- | :------------------- | :------------------- | :------------------- | :------------------- |
| Wired| Expensive | Faster | Higher | Lower |
| Wireless | Cheaper | Slower | Lower | Higher |
---

## WiFi ##
### SSID ###
- Name of the WiFi
- e.g. "stmarks_wifi_5g" , "You mum was busy yesterday"

### Key ###
- Password
- Similar to house with door lock
- Encrpytion = paper shredder 
- Disadvantage : 
    - Security (Can get the password)
    - Max speed
    - Interference by surrounding 

### Frequency ###
- e.g. 802.11a (2.4 GHz) , 802.11ac (5GHz) , 802.11ax
- Higher frequency = shorter range 

- e.g. 4G , 4G LTE , 5G
- fixed IP 

### T-carrier (P.205) ###
- Provides a permanent connections between network server and ISP's server 
- Allow network users to access internet simultaneously 
