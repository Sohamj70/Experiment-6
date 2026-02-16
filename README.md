### **Experiment – 6**
### **Aim** : Study of Conditional Statements in Python

### _**THEORY**_
- conditional statements in Python are used to make decisions based on given conditions.
- They allow a program to execute different blocks of code depending on whether a condition is true or false.
- Python uses if, elif, and else statements for decision making.
- The if statement checks the first condition and executes its block if the condition is true.
- The elif statement checks additional conditions when the previous condition is false.
- The else statement executes when none of the conditions are satisfied.
- Relational operators such as >, <, ==, >=, and <= are used to compare values.
- Logical operators like and, or, and not are used to combine multiple conditions.
- The modulo operator (%) is used to determine whether a number is even or odd.
- Conditional statements are commonly used in grading systems, validations, and number classification programs.
- Leap year checking is performed using conditional logic and mathematical rules.
- Date increment programs use conditions to handle month and year changes correctly.
- These concepts help improve logical thinking and problem-solving skills in Python programming.

### _**ALGORITHMS**_
- Algorithm 1: Check Whether a Number is Positive, Negative, or Zero
1. Start
2. Read a number from the user
3. If number > 0, print Positive
4. Else if number == 0, print Zero
5. Else, print Negative
6. Stop

- Algorithm 2: Check Whether a Number is Even or Odd
1. Start
2. Read a number from the user
3. If number modulo 2 equals 0, print Even
4. Else, print Odd
5. Stop

- Algorithm 3: Find the Largest of Three Numbers
1. Start
2. Read three numbers from the user
3. Compare the first number with the second and third
4. If the first number is greatest, print it
5. Else if the second number is greatest, print it
6. Else, print the third number
7. Stop

- Algorithm 4: Calculate Grade Using If-Elif-Else
1. Start
2. Read marks from the user
3. If marks ≥ 90, print Grade A
4. Else if marks ≥ 75, print Grade B
5. Else if marks ≥ 60, print Grade C
6. Else if marks ≥ 40, print Grade D
7. Else, print Fail
8. Stop

Algorithm 5: Check Leap Year
1. Start
2. Read year from the user
3. If year is divisible by 400, it is a leap year
4. Else if year is divisible by 4 and not divisible by 100, it is a leap year
5. Else, it is not a leap year
6. Stop

- Algorithm 6: Increment a Date by One Day
1. Start
2. Read day, month, and year from the user
3. Store number of days in each month
4. Check leap year and update February days if required
5. Increase day by 1
6. If day exceeds the maximum days of the month:
7. Set day = 1
8. Increase month by 1
9. If month exceeds 12:
10. Set month = 1
11. Increase year by 1
12. Display the next date
13. Stop

- Algorithm 7: Gross Salary Calculation
1. Start
2. Read basic salary
3. If basic ≤ 10,000, set HRA = 20% and DA = 0%
4. Else if basic ≤ 20,000, set HRA = 25% and DA = 90%
5. Else, set HRA = 30% and DA = 95%
6. Calculate Gross Salary = Basic + HRA + DA
7. Display gross salary
8. Stop
   
- Algorithm 8: Income Tax Calculation
1. Start
2. Read annual income
3. If income ≤ ₹2,50,000, tax = 0
4. Else if income ≤ ₹5,00,000, tax = 5% of excess income
5. Else if income ≤ ₹10,00,000, calculate tax using 5% and 20% slabs
6. Else, calculate tax using 5%, 20%, and 30% slabs
7. Display tax amount
8. Stop
   
- Algorithm 9: Vowel or Consonant Check
1. Start
2. Read a character
3. If the character is a vowel, display “Vowel”
4. Else, display “Consonant”
5. Stop

- Algorithm 10: Date Increment Program
1. Start
2. Read date in dd/mm/yyyy format
3. Separate day, month, and year
4. Find maximum days of the given month
5. If date is invalid, stop
6. If the day is the last day of the month:
7. Reset day and increase month/year
8. Else, increment day by 1
9. Display the next date
10. Stop

### _**CONCLUSION**_
These programs demonstrate the effective use of conditional statements in Python for solving real-life problems.
They help in understanding decision-making logic, comparisons, and control flow.
Conditional statements form the foundation for writing efficient and logical Python programs.
