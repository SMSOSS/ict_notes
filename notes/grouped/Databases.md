# Databases # 

## Table of Content ## 
| Table of Content |
| :------------------- | 
| [Source](#Source)|
| [Homework](#Homework) |
| [Structure](#CStructure) |
| [Key/primary Field](#Key/primary-Field) |
| [Common Data Types](#Common-Data-Types) |
| [SQL Commands](#SQL-Commands) |
| [Question Types in DSE](#Question-Types-in-DSE) |
| [Notes and Command Mistakes](#Notes-and-Command-Mistakes) |
| [Keywords](#Keywords) |

## Source ##
| SQL | 
| :------------------- | 
| [1 November 2021](/notes/01Nov.md) |
| [10 November 2021](/notes/10Nov.md) | 

## Homework ##
[google form](https://classroom.google.com/u/1/c/Mzg3ODYwNTYwNDU0/a/NDI1Nzk0NjQwNzI5/details)

---

## Structure ##
```
Database
- Table 1
    - Fields...
- Table 2
```
-  Similar structure with spreadsheet software (e.g. Excel)
    - Database is relatively more complicated as compared with
    - Database isn't able to generate charts (spreadsheet software can)
    - Database is good at handling large amount of data (spreadsheet software slow in handling + hard to share data scross sheets)
    - spreadsheet software is usually used to generate human-readable reports
-  With proper commands , it can easily filter data needed
-  Data types are case-sensitive on data type (text/number)
-  If wrong data type are used -> no data will be saved

---

## Key/primary Field ##
-  Contains data thats needed and all are unique
-  Possible to combine two keyfields (e.g. combining class & class number will create a unique key field)
-  If there is no key field -> give the data a unique ID (e.g. `0001`) to classify the data

---

## Common Data Types ##
Before we start, these are mostly shared in **C(++)** so if you have knowledge in **C(++)** it should be relatively easy
-  `INT` (Stands for integer , no decimal places will be stored)
    - `INT 24.96` will be stored as 24
- `FLOAT` (Stands for float, can store decimal places)
    - `FLOAT 24.96` will be stored as 24.96
-  `TEXT` (Stands for text. Can store any character / symbol. Uses relatively more space then `CHAR` as `TEXT` reserves space for large strings)
-  `CHAR` (Stands for character. Does not work without supplying character length.)
-  `DATE` (Stands for date. Only takes input in the format `YYYY-MM-DD` )
-  There are still lots of data types in database. However, only the 5 listed above will be tested in DSE (usually).

---

## SQL Commands ##
-  SQL stands for "Structured Query Language 
-  exam only required `SELECT`

### `SELECT` ###
-  Used to select data from database
-  Usage:
    - To show the names of `Students` in the database `Record`
        - `SELECT Students FROM Record;`
    - To show the different `Sex` in the database `Record`
        - `SELECT DISTINCT Sex FROM Record;`

### `DELETE` ###
-  Used to delete data from database.
-  Usage:
    - To delete from the database `Record` if `Sex` is `M`
        - `DELETE FROM Record WHERE Sex='M';`
    - To delete all records in the table `Record`
        - `DELETE * FROM Record;`

### `INSERT` ###
-  Used to insert data into database.
-  Usage:
    - To insert `pig` into the database `Record` with the columns `Name` and `Type`
        - `INSERT INTO Record (Name, Type) \n
           VALUES ('pig', 'boar');`       

### `UPDATE` ###
-  Used to update values in database.
-  Usage:
    - To update the type `Type` to `saber simp` where type `Name` is `pig` in the database `Record`
      - `UPDATE Record \n
         SET Type='saber simp' \n
         WHERE NAME='pig';`

---

## Question Types in DSE ##         
Mainly 2 types
-  Write output with given SQL commands
-  Write command with given SQL output

---

## Notes and Command Mistakes ##
-  The output data should be in raw output form. 
    - Do NOT output it in chart / format the output. It is NOT used for presentation.
-  Common mistake 1: Adding titles to the output
	- Unnecessary and no SQL software does such thing.
-  Common mistake 2: Using commas to separate data
	- Commands are only used on commands. Use spaces to separate data.

## Keywords ##
-  ...