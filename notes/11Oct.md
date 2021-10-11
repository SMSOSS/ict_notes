# ICT lesson, 11 October 2021 notes #

### Quick recap ###
- Need to memorize instructions of functions. No instructions will be given on the functions.
- Memorize all functions before exam.

### 1. Microsoft Excel ###
- Relative cell reference VS absolute (fixed) cell reference (add dollar sign `$` to make it fixed).
- Autofill (Excel will try to find out the pattern and fill out the remaining cells.)
- Functions:
    - Total number of cells with contents
    - `COUNTIF` used to find certain set of data in a specified number of cells.
        - Syntax: `COUNTIF(Cell start : Cell end, "Data range")`
    - Large used to find the nth largest number in a bunch of numbers
        - Syntax: `LARGE(range, number sequence)`
    - Small used to find the nth smallest number in a bunch of numbers
        - Syntax: `SMALL(range, number sequence)`
    - Median used to find the Median in a bunch of numbers
        - Syntax: `MEDIAN(range)`
    - Mode used to find the Mode in a bunch of numbers
        - Syntax: `MODE(range)`
    - Sum used to sum a range of numbers
        - Syntax: `SUM(range)`
    - Sumif used to sum a range of numbers with conditionals.
        - Syntax: `SUMIF(range of numbers, "=Condition", range of condition)`
    - If used to sort data.
        - Syntax: `IF(condition, "output if condition is fulfilled", "output if condition is not fulfilled)`
        - Can be used to do else if (how stupid lol).
    - Round used to round off numbers.
        - Syntax: `ROUND(cell number, decimal places)`
    - Roundup used to round up numbers.
        - Syntax: `ROUNDUP(cell number, decimal places)`
    - Rounddown used to round down numbers.
        - Syntax: `ROUNDDOWN(cell number, decimal places)`
    - Random used to output random decimal number between 0 and 1.
        - Syntax: `RAND()`
            - Advanced: Generate a number between 0 and 40.
                - Syntax: `RAND()*40`
            - Advanced: Generate a number between 1 to 100. (0 is not accepted)
                - Syntax: `RAND()*99+1`
            - Advanced: Generate random number between 40 to 60.
                - Syntax: `RAND()*20+40`
    - Randbetween used to generate random number between given range.
        - Syntax: `RANDBETWEEN(smallest number, largest number)`
            - RANDBETWEEN does NOT generate numbers with decimals
            - RANDBETWEEN is NOT allowed in DSE (wtf)
    - Mod feature used to get remainder of number
        - Syntax: `MOD(number, divider)`
    - Power feature used to get power of the certain number
        - Syntax: `POWER(number, power)`