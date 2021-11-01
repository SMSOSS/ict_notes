# 1 November 2021, ICT lesson notes ##

## Database ##

## structure ## 
Database 
  - Table1  
    - Fields
    .
    .
    .
  - Table2
  .
  .
  .
  .
  
- Has a similar structure with spreadsheet software (e.g. Excel)
  - Database is relatively more complicated as compared with spreadsheet software
  - Database isn't able to generate charts (however spreadsheet software can)
  - Database is good at handling large amount of data.
    - Spreadsheet software is slow in handling large amount of data.
    - It is also hard to share data across sheets in spreadsheet software. 
- With proper commands, one can easily filter data he/she needs.
- Database is usually used to store large amounts of data, and spreadsheet software is usually used to generate human-readable reports.
- Filter names
  - Data types are case-sensitive on data type. It should be in text or number.
  - If you use wrong data type, no data will be saved.
- Key / primary view
  - View contains data that's needed, and are all unique.
  - It is possible to combine two key views. (For example, combining class and class number will create a unique key view.)
  - If there is no key view, you can give the data a unique ID (e.g. `0001`) to classify the data.

## Common data types ## 
Before we start, these are mostly shared in C(++) so if you have knowledge in C(++) it should be relatively easy.
- `INT` (Stands for integer , no decimal places will be stored.)
  - `INT 24.96` will be stored as 24.
- `FLOAT` (Stands for float, can store decimal places.)
  - `FLOAT 24.96` will be stored as 24.96.
- `TEXT` (Stands for text. Can store any character / symbol. Uses relatively more space then `CHAR` as `TEXT` reserves space for large strings)
- `CHAR` (Stands for character. Does not work without supplying character length.)
- `DATE` (Stands for date. Only takes input in the format `YYYY-MM-DD` )
- There are still lots of data types in database. However, only the 5 listed above will be tested in DSE (usually).

## SQL commands ##
- SQL stands for "Structured Query Language".
- `SELECT`
  - Used to select data from database.
  - Usage:
    - To show the names of `Students` in the database `Record`
      - `SELECT Students FROM Record;`
    - To show the different `Sex` in the database `Record`
      - `SELECT DISTINCT Sex FROM Record;`
- `DELETE` 
  - Used to delete data from database.
  - Usage:
    - To delete from the database `Record` if `Sex` is `M`
        - `DELETE FROM Record WHERE Sex='M';`
    - To delete all records in the table `Record`
        - `DELETE FROM Record;`
- `INSERT` 
  - Used to insert data into database.
  - Usage:
    - To insert `pig` into the database `Record` with the columns `Name` and `Type`
        - `INSERT INTO Record (Name, Type) \n
           VALUES ('pig', 'boar');`
- `UPDATE`
  - Used to update values in database.
  - Usage:
    - To update the type `Type` to `saber simp` where type `Name` is `pig` in the database `Record`
      - `UPDATE Record \n
         SET Type='saber simp' \n
         WHERE NAME='pig';`

made by tkt0506 and only tkt0506