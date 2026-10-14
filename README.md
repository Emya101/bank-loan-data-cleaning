# Bank Loan Data Cleaning (Pandas)

A small data-cleaning exercise in Python using Pandas and Matplotlib. It examines data types, missing values and duplicates; normalizes `CCAvg` strings to numeric values; makes a histogram; and writes a cleaned CSV.

## Run
```bash
pip install -r requirements.txt
jupyter notebook bank_loan_data_cleaning.ipynb
```
Run the notebook top to bottom.

## Data source and limitation
`data/bank_loan_example.csv` is **synthetic test data** made specifically for this public version. It has 42 rows, including 2 duplicate rows. The original 5,000-row dataset was not supplied, so its results could not be reproduced. Do not describe results from this example as real bank findings.

The transformation `1/60` → `1.60` assumes the slash represents a decimal separator **only in this example**. Verify that convention before applying the code to other data.

## Skills demonstrated
Pandas, CSV imports, `info`, missing-value checks, duplicate detection/removal, string cleaning, type conversion, descriptive statistics, Matplotlib, CSV export.
