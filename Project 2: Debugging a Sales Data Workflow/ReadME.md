# Debugging a Sales Data Workflow

This project focuses on fixing a broken sales data pipeline by identifying and resolving issues inside the load_and_check() function. The dataset contains transaction records including quantity, price, tax, and totals. The goal is to ensure the function loads the data correctly and passes all integrity checks without modifying the original dataset.

## 📁 Dataset


The dataset used is available as:  
`data/sales.csv`

It includes key fields like:

- Quantity
- Unit price
- Total (Quantity × Unit Price)
- Tax (5% of the subtotal)
- Date


## 🎯 Project Goals

The goal is to troubleshoot and correct issues within the load_and_check() function by:

- Ensuring the dataset shape matches expectations.
- Recalculating the Total and Tax columns correctly inside the function.
- Passing two success checks:
  - "Data loaded successfully"
  - "Data integrity check was successful!"
- Maintaining the original data file without external modification.


## 🛠️ Tools & Technologies
- Python
- Pandas – data handling and manipulation
- NumPy – numerical operations
- Jupyter Notebook / Python scripts

## 🚀 How to Run
1. Clone this repository.
2. Ensure the sales.csv file is placed inside the data/ folder.
3. Run the Python script or notebook containing the load_and_check() function.
4. Verify that the output shows two success messages.

