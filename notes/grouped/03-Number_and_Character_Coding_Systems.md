# Number and Character Coding Systems #

## Table of Content ## 
| Table of Content |
| :------------------- | 
| [Source](#Source)|
| [Homework](#Homework) |
| [Representation of Data](#Representation-of-Data) |
| [Unit in Measuring Data](#Unit-in-Measuring-Data) |
| [How is Negative Values Stored in PC ?](#How-is-Negative-Values-Stored-in-PC-?) |
| [Keywords](#Keywords) |

## Source ##
| Represntation of Data |
| :------------------- | 
| [29 November 2021](/notes/29Nov.md) |
| [2 December 2021](/notes/02Dec.md) |

## Homework ##
[google form](https://classroom.google.com/u/1/c/Mzg3ODYwNTYwNDU0/a/NDQxMzE1ODI1MDE0/details)

---

## Representation of Data ##
-  Data are stored as 0 (no electricity) and 1 (have electricity) in computer 
-  In binary numbers , every digit is a **bit** (convert denary/hexadecimal into binary)
-  Hexadecimal usage : IP Adresses (IPv6) , Color Codes (#FFFFFF)
-  Types of representation of data : Text , Image , Audio , Video

---

## Unit in Measuring Data ##
- 1bit = 1b
- 8bit = 1 byte = 1B
- 1024B = 1 Kilobyte = 1KB
- 1024KB = 1 Megabyte = 1MB
- 1024MB = 1 Gigabyte = 1GB
- 1024GB = 1 Terabyte = 1TB
- 1024TB = 1 Perabyte = 1PB
- 1024PB = 1 Yetabyte = 1YB
- 1024YB = 1 Zetabyte = 1ZB 
- And so how everything goes on...
- Note: 1024 = 2^10

---

## How is Negative Values Stored in PC ? ##
### **Sign and magnitude** ### 
- leftmost bit represent positive(0) / negative(1)
- e.g. `1001` is -1 and `0001` is 1

### **Two's complement** ###
- Specify the number of bits (e.g. 8)
- e.g. -14
    - `00001110` = 14
	- Revert all the 0 and 1 -> `11110001` 
	- Two's complement of -14 -> `11110010` (add 1 at the end of the number)
	- so dumb and annoying (yes i agree)

## Data representation about text ##
-  **ASCII** (Amverican Stard Code Information Intercharge) 
    - data represented : 2^7
    - max value : 2^8
    - labels every character in your PC -> widely used and verified in the world
-  **Big5**
    - max value : 65536(2^16)   
    - Chinese character encoding method
    - GuoBiao is different with Big5 (for Simpified Chinese)
-  **Unicode**
    - 32Bit
    - UTF(bit) = Unicode Table    

---

## Keywords ##
-  Sign and magnitude
-  Two's complement
-  ASCII
-  Big5
-  Unicode
-  GuoBiao
-  this part completely useless lol
