# Spreadsheets #

## Table of Content ## 
| Table of Content |
| :------------------- | 
| [Source](#Source)|
| [Homework](#Homework) |
| [Types of Chart/Data](#Types-of-Chart/Data) |
| [Excel Functions](#Excel-Functions) |
| [Lookup Commands in Excel](#Lookup-Commands-in-Excel) |
| [Pivot Table](#Pivot-Table) |
| [What-if analysis / scenario merging](#What-if-analysis-/-scenario-merging) |
| [Keywords](#Keywords) |


## Source ##
| Spreadsheets |
| :------------------- | 
| [4 October 2021](/notes/04Oct.md) |
| [6 October 2021](/notes/06Oct.md) |
| [11 October 2021](/notes/11Oct.md) |
| [27 October 2021](/notes/27Oct.md) |
| [28 October 2021](/notes/28Oct.md) |

## Homework ##
[google form](https://classroom.google.com/u/1/c/Mzg3ODYwNTYwNDU0/a/NDIyMTk2MTE3Mzky/details)

---

## Spreadsheets ##
### Basic Information ###
-  Used for data analysis
-  Max Rows = `XFD` , Max Columns = `1048576`
-  Cell Address = Row number + Column number (e.g. `A1`)
-  Format cells(Data type)
    - Category. Self detecting may cause problems (e.g. mess formatting with extra zeroes)
        - e.g. Numbers, Text, Date, Percentage, etc.
        - After switching to text, formatting will be different with numbers. Sorting by ascending 
    - Important in Excel -> pay attention to data type

### Absolute Cell Reference/Fixed Cell Reference($) ###
-  Add $ -> no change character (e.g. `A1*$C$1` -> `A2*$C$1`)
-  Left/right -> change alpha(a,b,c)
-  Up/down -> change number(1,2,3)
-  Question : copy equation to address , change what value ?

### Auto Fill ###
-  Copy 1,2,3 -> continue 4,5,6...
-  text/number/abc
-  A,B,C,D -> continue A,B,C,D

### Cell Targeting ###
-  `A1:B3` = Select all cells within range(A1 to B3)
    - `A1~B3` , `A1-B3` are NOT accepted as they have other functions in Excel
-  `A1:B3 , C1:D3` = Select all cells within either on range (A1 to B3 or C1 to D3)

---

## Types of Chart/Data ##
### Types of Chart ###
-  Bar chart(separated bars for discrete data -> non-separated bars/histogram fro continous data)
-  Pie chart
-  Line Chart(continuous data)
-  Scatter disgram(show relationship between data)

### Types of Data ###
-  Continuous data
-  Discrete data/categonical data (non-continuous)
-  Question : give scenario/example to choose type of diagram

---

## Operators ##
### Arithmetical Operators ###
- plus : `+`, minus : `-` , `*`(multiply) , `/`(divide) , `%` (quotient), `^` (power)

### Logical Operators ###
- `=` (equal) , `<` (smaller) , `<=` (smaller or equal to) , `>` (larger), `>=` (larger or equal to), `<>` (not equal)
- `==` (equal in C programming) , `!=` (not equal in C programming)
- `&`(text concatenation)
- `" "`(strings, non-numbers / mixed characters and numbers)

---

## Excel Functions ##
### `MAX` ###
-  Used to show the **largest** number in a set of data
-  Usage : `MAX(range)`

### `MIN` ###
-  Used to show the **smallest** number in a set of data
-  Usage : `MIN(range)`

### `COUNT` ###
-  Used to count cells with data (numbers)
-  Usage : `COUNT(range)`
-  Can add additional arguments , depends on usage

### `COUNTIF` ###
-  Used to count cells with specific data
-  Usage : `COUNTIF(range , "filter:)`
-  E.g. : `COUNTIF(A1:A12 , ">100")` -> count cells that >100 in range A1 to A12

### `AVERAGE` ###
-  Used to find the **average** of a set of numbers
-  Usage : `AVERAGE(range)`

### `LARGE` ###
-  Used to find the **nth largest** number in range
-  Usage : `LARGE(range , number sequence(n))`

### `SMALL` ###
-  Used to find the **nth smallest** number in range
-  Usage : `SMALL(range , number sequence(n))`

### `MEDIAN` ###
-  Used to find the **median(middle number)** in range
-  Usage : `MEDIAN(range)`

### `MODE` ###
-  Used to find the **mode** in range
-  Usage : `MODE(range`)

### `SUM` ###
-  Used to find the **sum** in range
-  Usage : `SUM(range)`

### `SUMIF` ### 
-  Used to find the **sum** in range **with conditionals**
-  Usage : `SUMIF(range , "=condition" , range of condition) 
-  E.g. `SUMIF(A1:A5 , ">1" , B1:B5)` -> if `A1` > 1 -> +`B1`

### `IF` ###
-  Used to **sort data**
-  Usage : `IF(condition , "output if condition is fullfilled" , "output if condition is not fulfilled")`
-  Can be used to do elseif (how stupid lol)

### `ROUND` ###
-  Used to **round off** number
-  Usage : `Round(cell number , decimal places)`

### `ROUNDUP` ###
-  Used to **round up** number
-  Usage : `ROUNDUP(cell number , decimal places)`

### `ROUNDDOWN` ###
-  Used to **round down** number
-  Usage : `ROUNDDOWN(cell number , decimal places)`

### `RAND` ###
-  Used to output **random number** between 0 and 1
-  Usage : `RAND()`
-  Advanced : `RAND()*(b-a)+a` -> generate number between **a** to **b**

### `RANDBETWEEN` ###
-  Used to generate **random number** between **given range**
-  Usage : `RANDBETWEEN(smallest number , largest number)`
-  It does NOT generate numbers with decimals 
-  It is NOT allowed in DSE (wtf)

### `MOD` ###
-  Used to get **reminder** of number
-  Usage : `MOD(cell number , divider)`

### `POWER` ###
-  Used to get **power** of number
-  Usage : `POWER(cell number , power)`

### `LEN` ###
-  Used to calculate **length** in a text
-  Usage : `LEN(range)` 

### `LEFT` ###
-  Used to **cut string** from the **left** hand side of range
-  Usage : `LEFT(range , length of string to cut)`
-  E.g. `LEFT(A1 , 3)` -> A1="bad apple" -> "bad"

### `RIGHT` ###
-  Used to **cut string** from the **right** hand side of range
-  Usage : `RIGHT(range , length of string to cut)`
-  E.g. `RIGHT(A1 , 5)` -> A1="bad apple" -> "apple"

### `MID` ###
-  Used to **cut string** from range
-  Usage : `MID(range , start length , length of string to cut)`
-  E.g. : `MID(A1 , 5 , 5)` -> A1="bad apple" -> "apple"
-  E.g. : `MID(A1 , 1 , 3)` -> A1="bad apple" -> "bad"

---

## Lookup Commands in Excel ##
### `vlookup` ###
-  Used to **filter** value
-  Usage : `VLOOKUP(cell number , table , column(start from left) , TRUE(similar ok)/False(all same , usually set false))`

### `hlookup` ###
- Similar to `vlookup`
- `vlookup` find column , `hlookup` find row

---

## Pivot Table ##
-  GUI function (Insert -> Pivot Table)
-  Select range of the table (in the table/range option)
-  Table will not be generated immediately -> have to specify row/column/values
-  Filters : choose to hide the unwanted data

--- 

## What-if analysis / scenario merging ##
- What-if analysis can allow you to store multiple sets of data in a cell.
    - Useful when you want to see different results with different values.
    - Some examples are scenario merge and goal seek.

---

## Keywords ##
- too tired no make la

