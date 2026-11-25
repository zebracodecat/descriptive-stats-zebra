# descriptive-stats-zebra
Assignment 06: Descriptive Statistics

CHIP 705 – Assignment 06: Descriptive Statistics

Project Overview

This project analyzes synthetic patient demographic and clinical data to calculate estimated glomerular filtration rate (eGFR), identify patients with reduced kidney function, and summarize descriptive statistics.

Data Sources

The project uses two datasets provided for CHIP 705:

patient_demographics.csv – Patient age, height, weight, sex, and patient ID.

cmp.json – Clinical measurement data, including serum creatinine.

Analysis Plan

Import Libraries and Data

Import Pandas and Matplotlib.

Load the patient demographics CSV file.

Load the CMP JSON file.

Prepare the Data

Select the demographic columns needed for analysis.

Calculate patient BMI using height and weight.

Extract serum creatinine measurements from the CMP data.

Merge the demographic and creatinine data using patient ID.

Calculate eGFR

Calculate eGFR using the 2021 CKD-EPI Creatinine Equation.

Create a final DataFrame containing:

Patient Age

Patient Height

Patient Weight

Patient BMI

Patient Sex

Patient eGFR

Filter Patients

Identify patients with an eGFR less than or equal to 65.

Descriptive Statistics

Calculate descriptive statistics for patient age, height, and weight in the filtered dataset.

Visualizations

Create a bar chart showing average eGFR by BMI category.

Create a scatter plot showing patient age versus eGFR.

Create a pie chart showing patient sex distribution.

BMI Categories

Underweight: BMI below 18.5

Normal Weight: BMI 18.5–24.9

Overweight: BMI 25–29.9

Obese: BMI 30 or higher

Files

main.ipynb – Jupyter notebook containing the analysis and visualizations.

requirements.txt – Python package dependencies.

README.md – Project overview and analysis plan.

How to Run

Clone or download this repository.

Create and activate a Python virtual environment.

Install the required packages:

pip install -r requirements.txt

Open main.ipynb in Jupyter Notebook or VS Code.

Run the notebook cells from top to bottom.

Tools Used

Python

Pandas

Matplotlib

Jupyter Notebook

Data Note

The datasets used in this assignment contain synthetic data for educational purposes.
