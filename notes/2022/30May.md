# ICT lesson, 30 May notes #

## 1. IPv4 and IPv6 ##
- IPv4
    - Old, 8 bit x 4 set
    - Still mainstream in 2022

- IPv6
    - Newer, 4 digit hexadecimals x 8 sets
    - Made to solve IPv4 running out
    - P.234

- IP Classes (IPv6)
    - Class A
        - Starts with 0
        - 0 <network address> <host address> 
    - Class C
        - Starts with 1
        - (e.g. 192)
    - ALL Class A/B/C have parts that are reserved for internal use (a.k.a. Private IP)
    - Class D and Class E
        - Reserved for research purposes. Not for ordinary people
    - Network Address = Assigned number of network
    - Host address = Number of device in that network

## 2. How does websites (domains) work? ##
- Websites are actually stored somewhere else on a PC

- Your PC -> Enter domain -> Find the IP via DNS server -> DNS server tell you the IP -> Connect to web server via IP -> View website

![how-do-domains-work](/notes/2022/how-do-domains-work.jpg)

## 3. How a domain works ##

`
https://www/stmarks.edu.hk/web/index.php
`

- https://
    - Protocol
- www.
    - Sub-domain
- stmarks
- .edu
    - Second level domain
    - Website type
        - .com = Company / Commercial
        - .edu = Education
        - .net = Network Provider
        - .org = Non-profit Organization
        - .gov = Government
- .hk
     - first-level domain
     - Server region
- web/
    - Server folder
- index.php
    - File name
