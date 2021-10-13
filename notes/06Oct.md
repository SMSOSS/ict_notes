# ICT lesson, 6 October 2021 notes #


## types of charts ##
- bar chart(separated bars for discrete data , non-separated bars / histogram for continous data)
- pie chart
- line chart(continuous data)
- scatter diagram(show relationship between data)

## types of data ## 
- continuous data 
- discrete data / categonical data (non-continous)
- give scenario/example to choose type of diagram 

## spreadsheet - $ ##
- Address : A1 (X 1A)
- add $ (absolute cell reference / fixed cell reference) -> no change character 
    - Example : A1 * $C$1 -> A2 * $C$1
- left / right -> change alpha(a,b,c) 
- up / down -> change number(1,2,3)
- Question : copy equation to address , change what ? 

## spreadsheet - auto fill ##
- copy 1, 2 ,3 -> continue 4 , 5 ,6 ...
- text/number/abc 
- A , B, C , D -> continue A,B,C,D

## arithmetical operators ##
- plus : `+`, minus : `-` , `*`(multiply) , `/`(divide) , `%` (quotient), `^` (power)

## logical operators ##
- `=` (equal) , `<` (smaller) , `<=` (smaller or equal to) , `>` (larger), `>=` (larger or equal to), `<>` (not equal)
- `==` (equal in C programming) , `!=` (not equal in C programming)
- `&`(text concatenation)
- `" "`(strings, non-numbers / mixed characters and numbers)

## Functions ##
- `MAX` is used to show the largest number in a set of data.
    - Usage: `MAX(data range)`
- `MIN` is used to show the smallest number in a set of data.
    - Usage: `MIN(data range)`
- `COUNT` is used to count cells with data.
    - Usage: `COUNT(data range)`
    - Can add additional arguments, depends on usage.
- `COUNTIF` is used to count cells with specific data.
    - Usage: `COUNTIF(data range, "filter")`
    - For example, to count numbers that are larger than 100 in cells A1-A12:
        - `COUNTIF(A1:A12, ">100")`
- `AVERAGE` is used to find the average of a set of numbers.
    - Usage: `AVERAGE(data range)`
    - Known as `AVG` in database.

## Cell targeting ##
- `A1:B3` = Select all cells within range, from A1 to B3.
    - `A1~B3`, `A1-B3` are NOT accepted as they have other functions in Excel.
- `A1:B3 , C1:D3` = More than a range, in this case, 2 ranges, from A1 to B3 and from C1 to D3.

made by tkt0506

curate by ceb

excel really sucks