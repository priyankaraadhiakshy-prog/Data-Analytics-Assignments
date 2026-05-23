Data Analytics Assignments
All assignments and tasks for Data Analytics course.


Module 1 — Excel Assignment 1: Data Exploration


About This Assignment

This assignment is part of Module 1 of the Data Analytics course. I worked on a retail product dataset containing 34 rows and completed 5 tasks using Excel formulas and functions. The dataset includes product details like name, brand, price, quantity, and category.


Task 1 — Basic Data Exploration

Functions used: SUM, COUNT, AVERAGE

1. Total Price of All Products — Formula: =SUM(D2:D35) — Result: 10100
2. Count of Products — Formula: =COUNT(D2:D35) — Result: 34
3. Average Price — Formula: =AVERAGE(D2:D35) — Result: 297.06


Task 2 — Minimum and Maximum Values

Functions used: MIN, MAX

1. Minimum Price — Formula: =MIN(D2:D35) — Result: 30
2. Maximum Price — Formula: =MAX(D2:D35) — Result: 1000


Task 3 — Logical Function

Function used: IF

A Price Range column was added in Column G using the IF function.
Formula applied to G2:G35 — =IF(D2>=500,"High Price","Standard Price")
Products priced 500 and above are labelled High Price, others are Standard Price.


Task 4 — Conditional Functions

Functions used: SUMIF, COUNTIF

1. Total Price of Electronics Category — Formula: =SUMIF(F2:F35,"Electronics",D2:D35) — Result: 8050
2. Products with Price below 100 — Formula: =COUNTIF(D2:D35,"<100") — Result: 11


Task 5 — Text Functions

Functions used: LEFT, RIGHT, MID

The Product ID in Column A follows this format: DD-MON-CC (example: 28-JAN-US)

a. Day extracted using LEFT — Formula: =LEFT(A2,2) — Applied to H2:H35
b. Country Code extracted using RIGHT — Formula: =RIGHT(A2,2) — Applied to I2:I35
c. Month extracted using MID — Formula: =MID(A2,4,3) — Applied to J2:J35


Files Included

1. Excel Assignment 1 - Data Exploration.xlsx — Original assignment file provided by the instructor
2. Excel_Assignment_1_Data_Exploration_Completed.xlsx — Completed Excel workbook with all formulas
3. Data_Analytics_DA_Module_1_Excel_Assignment_1_Screenshots.pdf — Screenshots of all formula cells with results
