# ICT lesson , 25 May note #

## 17 - Communication software and Protocols ##
- protocols : format , rule 
- email protocols : send - SMTP , recv - IMAP , PoP

### sending / Reciving data ###
1. application 
2. presentation 
3. Session (Establishing connection)
4. Transport (Divide data in packets)
    - Transprot header packet + Packet + ...
5. Network (IP)
    - NH + TH + Data -> package
6. Data link
    - Data link header + packet + daat limit trailer -> error checking 
7. Physical


- 4th layer
    - TCP ( transmission central protocol)
- 5th layer
    - IP (internet protocol)

## IP ##
### IPv4 ###
- four set of number
- each set 8-bit(0~255)
- e.g : 2.9.4.87
- maximum :2^32

### IPv6 ###
- eight set of number
- each set 4-bit hexadacimal 
- e.g : C876 : 3927 : 3110 : AAAA : dddd : 2022 : 0007 : 4968
- maximum : 2^128