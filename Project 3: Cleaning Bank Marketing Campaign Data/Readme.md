# 🧹 Cleaning Bank Marketing Campaign Data

This project focuses on cleaning and reformatting a bank's marketing campaign dataset to prepare it for storage in a PostgreSQL database.  
The data is processed by splitting it into logical subsets, updating values, converting data types, and saving clean files for future analysis and database ingestion.



## 🎯 Project Goals

The goal is to use data cleaning techniques to:

- Modify specific column values (e.g., replacing `.` with `_` in job and education fields).
- Replace "unknown" education values with null (`NaN`).
- Convert appropriate fields to boolean, integer, and datetime types.
- Create three cleaned CSV subsets:
  - `client.csv`
  - `campaign.csv`
  - `economics.csv`

Each file matches the data structure required for future database storage and easy ingestion.

---

## 🛠️ Tools & Technologies

- Python
- Pandas – data manipulation
- NumPy – numerical operations
- Jupyter Notebook / Python scripts

---

## 🚀 How to Run

1. Clone this repository.
2. Ensure the `bank_marketing.csv` file is placed inside the `data/` folder.
3. Run the notebook or Python script to process and clean the dataset.
4. The cleaned files will be saved as:
   - `client.csv`
   - `campaign.csv`
   - `economics.csv`

No manual edits to the original CSV file are needed — all cleaning happens programmatically.

---

## 📚 Skills Demonstrated

- Advanced data cleaning and wrangling
- Data type conversion
- Splitting datasets into logical subsets
- Preparing data for SQL database import
