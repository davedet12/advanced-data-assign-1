This repository contains data, analytic code, and findings for two analyses of pay for entry level public safety officers in NYC. These are limited to the city's three
largest departments by headcount -- DOC, NYPD, and FDNY. 

Data
Two analyses are included here. One is an incomplete analysis using the following spreadsheet: Citywide_Payroll_Data_(Fiscal_Year)_20251030.csv -- Raw data of New York City employees salary from October 2025. I ran into issues reformatting this data, and abandonded the analysis as a result. 

The second analysis -- which I consider completed -- uses the following spreadsheet: Citywide_Payroll_Data__Fiscal_Year__20240616.csv -- Raw data of New York City employees salary from June 2024. 

This spreadsheet contains, among others, the following columns relevant to the analysis: Total OT Paid — Amount of overtime paid to Correction's Employees; Base Salary — Base salary of each employee; Title Description - Description of Each Position of Corrections Members

Methodology
The notebook DeTurris-One-Last-Time.ipynb -- which uses the payroll data from October 2025 -- performs the following analyses:

Part 1: Remove dollar sign from salary amount to ease reclassification process; Part 2: Convert payment categories from objects to floats; Part 3: Limit analysis to only members of the Department of Corrections; Part 4: Attempt to provide summary of Department of Correction wages in time. Again, abandonded because there was an issue with formatting the data I couldn't figure out how to fix. 

The notebook DeTurris-DOC-Wages.ipynb -- which uses the payroll datd from June 2024 -- performs the following analyses:

Part 1: Limit the data to only give salaries and overtime payments for members of the Department of Corrections; Part 2: Limit data to only the Department's entry level position (in this case, Correction Officer); Part 3: Limit data to median salary and overtime payment from entry level workers over the past ten years, and save these as distinct dataframel Part 4: Repeat Parts 1 - 3 for NYPD and FDNY; Part 5: Concatenate data from each department into one dataframe; Part 6: Create bar graph to compare average salary and overtime pay for each department. 


Outputs
The notebook's output is a bar graph png, found in link along with data.

Data and Output Links
These can all be found in this Google Drive folder: https://drive.google.com/drive/folders/1uCan7ZLIbUZECq3KmpK-dwrZK36Sj_go?usp=drive_link

Running the analysis yourself
You can run the analysis yourself. To do so, you'll need the following installed on your computer:

Python 3
Licensing
All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

Feedback / Questions?
Contact David DeTurris at david.deturris98@journalism.cuny.edu.
