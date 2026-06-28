# Sleep and Stress Python Analysis

This is my first Python data analysis project. This project processes survey data from a Google Forms response spreadsheet to analyze relationships between variables. It was a collaborative effort between my partner Aurel and me when we were both complete beginners in Python. 

---

## How It Was Built
* Language: Python
* Libraries Used:
    * pandas - For loading the Excel data and reading row/column values.
    * numpy - For calculating data percentiles and managing arrays.
    * matplotlib - For creating the scatter plot and regression line.
    * math - For calculating averages and square roots used in the mathematical formulas.

## Project History
This project was originally built in **VS Code** as a local file on my computer back in **2023** when I first started self learning Python using online resources like W3Schools, Stack Overflow, and a bit of AI. For easier result viewing, I migrated the code into a Google Colab notebook. The repository contains the final `.ipynb` notebook file alongside the anonymized survey response spreadsheet.

## Core Features
* Data Ingestion - Loads the questionnaire response spreadsheet into Google Colab for processing.
* Data Scoring - Converts text survey answers into numerical scores to calculate sleep (PSQI) and stress (K10) metrics.
* Outlier Detection - Uses the Interquartile Range (IQR) method to find and remove outliers.
* Statistical Modeling - Builds a linear regression model using basic math formulas to analyze the relationship between sleep and stress.

## License
**All Rights Reserved.**  
This code is public for demonstration purposes only. It may not be copied or reused without permission.
