# Communication Software and Protocols #

## Table of Content ##
<!-- TOC -->

- [Communication Software and Protocols](#communication-software-and-protocols)
    - [Table of Content](#table-of-content)
    - [Source](#source)
    - [Communication Protocol](#communication-protocol)
    - [Open System Interconnection OSI Model](#open-system-interconnection-osi-model)
        - [Application Layer](#application-layer)
        - [Presentation Layer](#presentation-layer)
        - [Sessions Layer](#sessions-layer)
        - [Transport Layer](#transport-layer)
        - [Network Layer](#network-layer)
        - [Data Link Layer](#data-link-layer)
        - [Physical Layer](#physical-layer)
        - [Transmission Control Protocol TCP](#transmission-control-protocol-tcp)
        - [Internet Protocol IP](#internet-protocol-ip)
    - [IP](#ip)
        - [IPv4](#ipv4)
        - [IPv6](#ipv6)
        - [IP Classes IPv6](#ip-classes-ipv6)
    - [Domain](#domain)
        - [How a domain work](#how-a-domain-work)
        - [URL Uniform Resource Locator](#url-uniform-resource-locator)
        - [Protocols for web browsing ###](#protocols-for-web-browsing-)

<!-- /TOC -->


## Source ##
| [25 May 2022](/notes/2022/25May.md) - Network protocols (e-Mail & IP) |
| [30 May 2022](/notes/2022/30May.md) - IP (cont.) and URLs |
| [1 June 2022](/notes//2022/01June.md) - URLs (cont.) and protocols for web browsing |

---

## Communication Protocol ##
- Set of rules about data formatting or signalling that is understoaod by all the communication devices 
- Common standard 
- e.g. TCP (Transmission Control Protocol) , IP (Internet Protocol)

---

## Open System Interconnection (OSI) Model ##
- Data is transmitted from one computer to another computer

### 1. Application Layer ###
- Provide the interface for application software to set up communication with another application device 

### 2. Presentation Layer ###
- Convert data into a format that can be transmitted and compatible to receiver's system 

### 3. Sessions Layer ###
- Setting up and maintaining the communication session between two computers 

### 4. Transport Layer ###
- Add Transport Header (TH) to data to form datagram 
- TH contains the transportation information (e.g. protocol used)
- Using TCP -> divided into smaller packets before transmitting 

### 5. Network Layer ###
- Determines routing and forwarding data
- Add Network Header (NH) to datagram to form packet
- NH contains network address information 
- e.g. IP

### 6. Data Link Layer ###
- Resposible for network addressing / error detection and correction 
- Data Link Header (DLH) and Data Link Trailer (DLT) added to packet to form frame
- DLH contains physical address and method of error detection and correction
- DLT contains string of bits that indicates the end of packet 
- e.g. WiFi , Ethernet 

### 7. Physical Layer ###
- Transfer frames physically on a LAN 
- Resposible for managing the interaction between network medium and communication devices in computer 

### Transmission Control Protocol (TCP) ###
- Manage data packets and network information for routing
- Divided file into one or more packets 
- Packets are numbered and then forwarded one by one to IP layer
- TCP layer reassembles the received data packets into a single data file

### Internet Protocol (IP) ###
- Handle the actual delivery of data packets 
- Add the destination IP address to packets for routing packets to the destination through network server
- Responsible for packet fragmentation 
    - Maximum Transmission Unit may different 
- Selects shortest path to destination or choose alternative path network congestion 

---

## IP ##
- IP address , identify every computer in a network (unqiue)
- Consists of two parts 
    - Network address : Identify a particular network 
    - Host address : Identify particular device in network

### IPv4 ###
- Four set of number with each set 8-bit (0~255)
- maximum : 2^32
- e.g. `2.9.4.87`

### IPv6 ###
- Eight ser of number with each set 4-bit hexadecimal
- maximum : 2^128
- Can accommodate more IP address (solve IPv4 running out)
- e.g. `C876 : 3927 : 3110 : AAAA : dddd : 2022 : 0007 : 4968`

### IP Classes (IPv6) ###
- Class A
    - Starts with 0
    - `0 <network address> <host address>`
- Class C 
    - Starts with 1 
    - e.g. `192`
- All Class A/B/C have parts that are reserved for internal use (Private IP)
- Class D and E
    - Reserved for research purpose , not for ordinary people 
    - Network address = assigned number of network 
    - Host address = number of device in that network

---

## Domain ##
- Websites are actually stored somewhere else on a PC 
- Your PC -> Enter domain -> Fins the IP via DNS server -> DNS server tell you the IP -> Connect to web server via IP -> View website
![how-do-domains-work](/notes/2022/how-do-domains-work.jpg)

### How a domain work ###
`https://www/stmarks.edu.hk/web/index.php`

- `https://` : Protocol
- `www.` : Sub-domain
- `stmarks` : Third-level domain
- `.edu` : Second-level domain (Website type)
    - `.com` = Company / Commercial
    - `.edu` = Education
    - `.net` = Network Provider
    - `.org` = Non-profit Organization
    - `.gov` = Government
- `hk` : Fist-level domain (Server region)
- `web/` : Server folder
- `index.php` : File name

### URL (Uniform Resource Locator) ###
- Web address 
- www (world wide web) is only one of the subdomains
- Different subdomain traces to different server 
- Domain names have been asked multiple times in HKDSE
- URLs can be used in emails too!

### Protocols for web browsing ### 
1. HTTP / HTTPS (Encryption related )
    - HTTPS is relatively more secure and save your from man-in-the-middle attacks 

2. FTP (File Transfer Protocol)
    - Require FTP server 
        - Can be any computer installed with FTP server program
    - Connect by IP / Domain name using FTP clients
    - Online clients (e.g. onlineFTP) or Installed clients (e.g. Filezilla)
    - Client connect into server for transfer / receive work 
    - Very very specific channel , not Google Drive / Whatsapp / etc
    - Actually very efficient and fast 

3. SMTP (Protocol for sending email)
    - Emails have different protocol for receiving and sending 

4. IMAP (Protocol for receiving email)
    - Receiving email without downloading the email content from server

5. POP (3)
    - Used for receiving emails 
    - Download email content from server to local computer
    - Multi programs use it , e.g. Outlook & GMail

6. SSH (Secure Shell)
    - Remote control protocol 
    - Terminal-based environment 

7. DHCP 
    - IP assignment (assigns IP to your device)

8. DNS 
    - Mentioned before :)

9. SSL/TLS (Transport Layer Security)
    - (handshake)
    - Webpage Encryption (in HTTPS)

10. TCP / IP
    - Again , mentioned before :D

11. VoIP (Voice transmission via IP)
    - VoLTE / VoNR (voice over 4/5G)

12. Telnet 
    - Remote Control (usually used on Windows)
    - Probably terminal-based environment too 