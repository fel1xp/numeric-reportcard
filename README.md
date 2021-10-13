# numeric-reportcard

A practice exercise to keep my Ruby skills sharp. 

## Brief 

School Reports Company. Help teachers understand student performance over the year.
Accept multiple test entries, then generate a report with the average student mark for each test. 


## Input / Output Table

[68, 71, 85, 52]|
generate report | Test 1 - Average Score: 69



## Edge Cases
If string is entered, error message.
Each number cannot exceed 100.
Marks will be an integer. Average score to 1 decimal place if applicable. 
If no marks are added and report is generated, error message. 


### Approach
1 Class
2 Methods
1st Method - Add scores method, push into an array
2nd Method - Generate Report method. Average array values then print a string. 
