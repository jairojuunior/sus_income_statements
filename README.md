# SUS Income Statements
This repository contains scripts on the Brazilian Universal Healthcare System income statements. I collected and preprocessed in order to facilitate manipulation by the data community.


## High level data pipeline

1. Import files
2. Extract from file header the year of reference
2. Extract the IBGE city code
3. Convert objects to numeric (this dataset contains columns where the decimal separator is period or comma)
4. Export a CSV at `output_income_balances/health_income_balance_<year>.csv`
  
  ## How to run it?
  
  Run `Dataprep Notebook.ipynb` (instruction on notebook).
  
  ---
**NOTE**

This data pipeline was tested only with files from 2009 to 2019. It might not work on previous data.

---

## Where can I see exported data?

I update this data on Kaggle monthly. Get it: https://www.kaggle.com/jairofreitas/brazilian-universal-health-care-data

