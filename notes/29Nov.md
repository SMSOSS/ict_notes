# ICT Lesson, November 29 Notes #

## 1. Data ##
- Representation of Data
	- Data are stored as 0 and 1 in a computer
		- Have electricity and no electricity
	- Learn how to convert denary / hexadecimal into binary numbers :)
		- In binary numbers, every digit is a bit.
		- f3 math, go back to f3 if u don't know
		- Make sure to learn it as calculator can't help u every time :<
	- Hexadecimal usage
		- IP Adresses (IPv6)
		- Color Codes (#FFFFFF)
	- Types of representation of data
		- Text
		- Image
		- Audio
		- Video (Audio + Images)
	- Unit in measuring data
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
- How is negative values stored in binary in PC?
	- Sign and magnitude
		- The leftmost bit represent positive / negative.
		- 0 = positive and 1 = negative
			- e.g. `1001` is -1 and `0001` is 1
	- Two's complement
		- 1. Specify the number of bits (e.g. 8)
		- e.g. -14
			- `00001110` = 14
			- Revert all the 0 and 1 -> `11110001` 
			- Two's complement of -14 -> `11110010` (add 1 at the end of the number)
			- so dumb and annoying
