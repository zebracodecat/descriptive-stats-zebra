# CHIP 705 – Assignment 06: Descriptive Statistics

## Project Overview
This project analyzes synthetic patient demographic and clinical data to calculate estimated glomerular filtration rate (eGFR), identify patients with reduced kidney function, and summarize descriptive statistics.

## Data Sources
- `patient_demographics.csv` – Patient age, height, weight, sex, and patient ID.
- `cmp.json` – Clinical measurement data, including serum creatinine.

## Analysis Plan

1. Import Pandas and Matplotlib.
2. Load the patient demographics CSV and CMP JSON data.
3. Calculate BMI using patient height and weight.
4. Extract serum creatinine measurements and merge the datasets using patient ID.
5. Calculate eGFR using the 2021 CKD-EPI Creatinine Equation.
6. Create a final DataFrame containing Patient Age, Patient Height, Patient Weight, Patient BMI, Patient Sex, and Patient eGFR.
7. Filter patients with eGFR less than or equal to 65.
8. Calculate descriptive statistics for patient age, height, and weight.
9. Create the following visualizations:
   - Bar chart: Average eGFR by BMI category.
   - Scatter plot: Patient Age vs. eGFR.
   - Pie chart: Patient sex distribution.

## BMI Categories
- Underweight: BMI below 18.5
- Normal Weight: BMI 18.5–24.9
- Overweight: BMI 25–29.9
- Obese: BMI 30 or higher

## Files
- `main.ipynb` – Jupyter notebook containing the analysis and visualizations.
- `requirements.txt` – Python package dependencies.
- `README.md` – Project overview and analysis plan.

## How to Run

1. Clone or download this repository.
2. Create and activate a Python virtual environment.
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Open `main.ipynb` in Jupyter Notebook or VS Code.
5. Run the notebook cells from top to bottom.

## Tools Used
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Data Note
The datasets used in this assignment contain synthetic data for educational purposes.