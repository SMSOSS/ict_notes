# ICT Lesson, 17 November 2021 Notes #

## 1. Common data errors ##
- Data source error 
	- The given data already has errors
- Transcription error
	- Mainly typo mistakes
	- Can be made by Human / OCR software.
- Transposition error 
	- Mainly typo mistakes
	- Most of the time made by human
- Difference between transcription and transposition error
	- Transcription error is when the whole thing is wrong (wild pig -> wood pig)
	- Transpostion error is when the characters is misplaced (wild pig -> wlid pig)

## 2. Data validation methods ##
All methods below are used to ensure that data are valid.
- Field presence checks
	- Checks if field is being filled in
- Length checks
	- Checks length of input
	- Phone numbers have 8 digits, can check if phone number entry has 8 digits
- Range check
	- Check range of input
	- Age is <150, can check if age is valid by checking if value is smaller than 150
- Fixed value check
	- Check if value of input matches prefix
	- Sex is usually M/F, can check if sex is legit
- Format check
	- Check if format of input matches prefix
	- ID Card has special format, can check if ID number is legit
- Type check 
	- Check if data type is correct
	- Student Grades should be characters not numbers, can check if there is error in input
- Check digit 
	- Check if numeric data has the same length
	- Same as length checks

## 3. Data verification methods ##
- In order to reduce data errors:
    - Enter data twice
        - Same person enter data twice
    - Double entry
        - Different person enter data twice

    - Entering data twice can reduce error count as it is very rare that the two inputs will have the same error.