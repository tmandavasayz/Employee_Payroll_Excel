https://docs.google.com/spreadsheets/d/1qsWqlnzFW-RYRg_R_w_WyGUwzcrT_ARMnx7E2FLAPWg/edit?usp=sharing

Payroll Project 

Process:

    1. Created a workbook and added 15 employee names with hourly wages, number of hours worked and pay delivered 
    2. Formatted the hourly wages currency to Canadian dollar
    3. Calculated the pay by the number of hours * hourly wage
    4. Calculated the min, max and average salaries and the number of hours worked accordingly
    5. For the number of hours, reduce the decimal points by rounding off to the nearest tenths 
    6. For the total, calculate the total number of hours and total wages received.
    Project extension with IF statement: (For incentives)
    1. Insert a column before the Pay column and name it as Overtime 
    2. Total number of hours worked at any firm is 40 hours, and anything over that is overtime 
    3. =if(logical_test,[value_if_true],[value_if_false]) - to calculate if anyone is working less than 40, should not come in negatives
    4. =If(D4>40,D4-40,0) - If D4 is greater than 40 then return D4-40 else return 0
    5. =0.5*C4*E4 - Overtime bonus anyone is getting if worked greater than 40 hours
    Project extension with 4 more weeks of pay 
    1. Add more columns to add data for the rest of the weeks
    2. Cell number + 7 draws the next week exact date 
    3. Add the data for the number of hours worked
    4. Calculate the number of hours worked and overtime hours with the existing formula 
    5. To calculate the pay, use absolute cell referencing.
    Relative v/s absolute cell referencing:
    >>Relative cell referencing works for those cells with values performing similar functions 
    >>Absolute cell referencing is to work with a certain value with all other cell values - the hourly wage stays the same, but the number of hours worked every day differs in a week
    How?
    >> In the formula, add a $ sign before the cell value - this makes an absolute cell reference - even if the formula is copied, the main cell remains the same. 

Keypoints:

    1. Letters are left justified and numbers are right justified in MS Excel / Google Sheets
    2. Colors correspond to the cells in the formula 
    3. Sheets allow you to copy and paste the formulas and work for every column
    4. If you copy and paste the pay formula, it doesn’t work. Absolute cell referencing is needed in this case
