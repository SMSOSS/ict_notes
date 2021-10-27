# ICT lesson, 27 October 2021 notes #

## 1. Recap from last lesson ##
- MAX 
- MIN
- AVERAGE ( x AVG)
- COUNT
- COUNTIF
- LARGE
- SMALL
- MEDIAN
- MODE
- SUM
- SUMIF
- IF
- ROUND
- RAND
- RANDBETWEEN
- INT 
- MOD
- POWER 

- Will not explain these (takes too much time) again. Check pass notes. 

## 2. Excel Functions (continued) ##
- LEN
    - Stands for "Length", used to calculate length in a string (text).
    - Usage: `LEN(Cell range)`
- LEFT
    - Used to cut characters from the left hand side of a provided range.
    - Usage: `LEFT(Cell range, length of string to cut)`
        - Example: To cut the word "Bad" out of "Bad apple" in cell A1, the command would be: `LEFT(A1, 6)`
- RIGHT
    - Used to cut characters from the right hand side of a provided range.
    - Usage: `RIGHT(Cell range, length of string to cut)`
        - Example: To cut the word "apple" out of "Bad apple" in cell A1, the command would be: `RIGHT(A1, 4)`
- MID(take character from a position)
    - Used to cut strings from a bunch of strings
    - Usage: `MID(Cell range, starting length, length of string to cut)`
        - Example: To cut the word "apple" out of "Bad apple" in cell A1, the command would be: `MID(A1, 5, 5)`
        - Starting length:  The first 5 (starting length) is targeted on `a`, from left to right, including spaces.
        - Length of string to cut: Straightforward. In this example, I want to cut apple, so the string length is 5.

## 3. Lookup commands in Excel ##
- vlookup (data vertical) 
- hlookup (data horizontal)
- vlookup(input , table , column , FALSE/TRUE(true -> similar ok -> usually set false) )
- Ex : vlookup(G1 , A1:D20 , 4 , FALSE)
- check first column -> put input in first column (Ex : name )
- filter 

## pivot table ##  
- row , column , value , filter 
- oh no forgot to type :(

## what-if analysis / sceniro manage ##
made by tkt0506
