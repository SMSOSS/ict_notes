# Data Organization and Data Control #

## Table of Content ## 
| Table of Content                                        |
| :------------------------------------------------------ |
| [Source](#Source)                                       |
| [Homework](#Homework)                                   |
| [Common Data Errors](#Common-Data-Errors)               |
| [Data Validation Methods](#Data-Validation-Methods)     |
| [Data verification methods](#Data-verification-methods) |
| [Keywords](#Keywords)                                   |

## Source ##
| Data Validiation                    |
| :---------------------------------- |
| [17 November 2021](/notes/17Nov.md) |

## Homework ##
[google form](https://classroom.google.com/u/1/c/Mzg3ODYwNTYwNDU0/a/NDQxMzEzNTAzNjc1/details)

---

## Common Data Errors ##
### **Data source error** ###
-  The given data already has errors (tkt sleep at 10 everynight -> give data already wrong)

### **Transcription error** ###
-  Mainly typo mistakes ("Transportation Error")
-  Can be made by Human / OCR software
-  The whole character is wrong (wild pig -> wood pig ???)

### **Transposition error** ###
-  Mainly typo mistakes
-  Most of the time made by human
-  Character is misplaced (wild pig -> wlid pig)

---

## Data Validation Methods ##
### **Field presence checks** ###
-  Checks if field is being filled in 
-  always fill this, always right :)

### **Length checks** ###
-  Checks length of input
-  e.g. Phone numbers have 8 digits -> check if entry has 8 digits

### **Range check** ###
-  Check range of input 
-  e.g. Age < 150 -> check if value < 150

### **Fixed value check** ###
-  Check if value of input matches prefix 
-  e.g. Sex is usually M/F -> check if sex is legit

### **Format check** ###
-  Check if format of input matches prefix
-  e.g. ID Card has special format -> check if ID number is legit

### **Type check** ###
-  Check if data type is correct
-  e.g. Student Grades is character -> check if input is character

### **Check digit** ###
-  Check if numeric data has same length
-  Same as length checks

---

## Data verification methods ##
### **Enter data twice** ###
-  Same person enter data twice
-  e.g. change password need to enter twice to confirm 
-  reduce error count as it is rare that 2 inputs will have same error

### **Double entry** ###
-  different person enter data twice

---

## Keywords ##
- Data source error 
- transcription error 
- transposition error 
- range check 
- fixed value 
- type check 
- format check 
- length check 
- data presence check 
- enter data twice 
- double entry 
