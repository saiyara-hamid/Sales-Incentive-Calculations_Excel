# Sales-Incentive-Calculations_Excel
This repository contains an Excel-based incentive calculation model designed to demonstrate advanced Excel skills in managing sales compensation for the sales force of a pharmaceuticals company.

## Project Overview
The entire project is consolidated within a single Excel workbook (`incentive calculations_WIP.xlsx`). This workbook includes multiple sheets that walk through the process of calculating sales incentives from data cleaning to final payout calculations. Data has been sourced from personal repositories and masked and changed to ensure confidentialy.

### Sheets in the Workbook

1. **Rules**:
   - This sheet outlines a simple sales compensation plan for the sales force. In reality, different category of employees and sales divisions create further complexities which have been avoided for this project. This has been done to ensure audience's ease of readability.
   - It provides the structure and rules used for calculating incentives based on sales performance.

2. **Sales RAW Data and Employee List**:
   - There are 2 sheets with 2 databases that have been the cleaned and connected, including sales data by territory, brand, and month, and the employee list.
   - The data is linked using Territory Code and Employee ID as primary keys.

3. **Payment Plan**:
   - This sheet serves as the payment reference according to the incentive scheme (rules).
   - All relevant payout percentages and conditions are documented here.

4. **Incentive Calculation**:
   - The main framework for calculating incentives.
   - Formulas are included to compute incentive earnings for each employee based on the sales data and the rules defined in the incentive scheme. Simple V-Lookup, X-Lookup and complex nested formulas and IF/THEN and SUMIFS have been used primarily to get the desired results.
   - Key calculations are made visible to answer potential queries from employees.
   - Manual adjustements have been made to address issues such as abrupt reposting (territory change) and resignations, which is a common occurance in the corporate world. 

6. **Highlights**:
   - A summary sheet that provides a brief snapshot of the number of employees, sales figures, and total incentive earnings.
   - It includes charts and other visual elements to present data in an easily digestible format.

## How to Use

1. **Open the Workbook**:
   - The entire project is encapsulated in the `incentive calculations_WIP.xlsx` file.

2. **Navigate the Sheets**:
   - Start by reviewing the **Incentive Scheme** sheet to understand the compensation plan.
   - Follow the sheets in sequence to see how the data is cleaned, connected, and used to calculate incentives.
   - The **Highlights** sheet gives a top-level view of the results.

3. **Understand the Formulas**:
   - The workbook is well-documented with explanations for key formulas and their logic.

## Key Excel Features Used
- **Data Cleaning**: Advanced techniques like VLOOKUP, INDEX-MATCH, and conditional formatting.
- **Formula Creation**: Nested IF statements, SUMIFS, and complex formulae for accurate incentive calculation.
- **Manual Adjustments**: Flexibility to override calculated values when necessary.
- **Data Visualization**: The Highlights sheet uses charts and conditional formatting for quick insights.
