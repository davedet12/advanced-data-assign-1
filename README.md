This repository contains data, analytic code, and findings that support portions of the article, "NYC's Corrections Department Wages Wax and Wane Over the Years",  published November 1, 2025. Please read that article, which contains important context and details, before proceeding.

Data
This incomplete analysis uses the following spreadsheet: Citywide_Payroll_Data_(Fiscal_Year)_20251030.csv: Raw data of New York City employees salary. Link here, since file is too big https://data.cityofnewyork.us/City-Government/Citywide-Payroll-Data-Fiscal-Year-/k397-673e/about_data.

This spreadsheet contains, among others, the following columns relevant to the analysis:

Total OT Paid — Amount of overtime paid to Correction's Employees; Base Salary — Base salary of each employee; Title Description - Description of Each Position of Corrections Members
Methodology
The notebook DeTurris-One-Last-Time.ipynb performs the following analyses:

Part 1: Remove dollar sign from salary amount to ease reclassification process; Part 2: Convert payment categories from objects to floats; Part 3: Limit analysis to only members of the Department of Corrections; Part 4: Attempt to provide summary of Department of Correction wages in time. 

Outputs
The notebooks output this spreadsheet which is found at the bottom of the notebook.

Running the analysis yourself
You can run the analysis yourself. To do so, you'll need the following installed on your computer:

Python 3
Licensing
All code in this repository is available under the MIT License. The data file in the output/ directory is available under the Creative Commons Attribution 4.0 International (CC BY 4.0) license. All files in the data/ directory are released into the public domain.

Feedback / Questions?
Contact YOUR NAME HERE at david.deturris98@journalism.cuny.edu.
