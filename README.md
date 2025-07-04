# Employee Data Analysis of Palmora Group
## Project Overview
This Power BI project analyzes employee data for Palmoria to 
uncover insights about gender distribution, performance ratings, 
salary structure, regulatory compliance, and bonus allocation. 
The goal is to assist management in decision-making and ensure 
compliance with salary regulations.

## Data source
The primary dataset used for this analysis is the Palmoria Group Employee Data csv file and
Palmoria Group Bonus Rule data excel file.

## Tools and Skills Used
Power Bi (For data cleaning and Analysis and Data visualization)

## Questions Addressed
1. What is the gender distribution in the organization? Distil to regions and 
departments 
2. Show insights on ratings based on gender 
3. Analyse the company’s salary structure. Identify if there is a gender pay gap. If 
there is, identify the department and regions that should be the focus of 
management 
4. A recent regulation was adopted which requires manufacturing companies to pay 
employees a minimum of $90,000 
- Does Palmoria meet this requirement?
- Show the pay distribution of employees grouped by a band of $10,000. For example: 
- How many employees fall into a band of $10,000 – $20,000, $20,000 – $30,000, 
etc.?
- Also visualize this by regions
5. Mr Gamma thought to himself that since you were already working on the employee 
data, you could help out with allocating the annual bonus pay to employees based on the 
performance rating. He handed you another data set that contains rules for making bonus 
payments and asked you to: 
- Calculate the amount to be paid as a bonus to individual employees
- Calculate the total amount to be paid to individual employees (salary inclusive of 
bonus)
- Total amount to be paid out per region and company-wide

## Implementation Details
All data transformations and calculations were done in Power Query (M Language), not DAX.
### Power Query Steps:
Merge EmployeeData with BonusRules using the Rating column.
### Bonus Calculation:
BonusAmount = [Salary] * [BonusPercent]
TotalPay = [Salary] + [BonusAmount]

## Results Visualization

![Palmora visual 3](https://github.com/user-attachments/assets/9ac4c9d5-b7c9-4824-bbf5-d182bef0d0ee)

![Palmora visual](https://github.com/user-attachments/assets/b0b31709-fb95-4387-9296-bb4c8f0b5eaf)

![Palmora visual 4](https://github.com/user-attachments/assets/c315b28e-fb8b-4df0-8686-aedfd089a7b2)

