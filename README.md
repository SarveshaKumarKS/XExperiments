# Project X — UberEats Data Cleaning & Flavor XD Pipeline

## Folder structure
```
project_x/
├── data_raw/
│   └── user_orders-0.csv
├── data_cleaned/
│   └── (outputs written here)
├── notebooks/
│   └── 01_data_cleaning.ipynb
├── requirements.txt
└── README.md
```

## Quick start
1. Create this folder structure on your local machine and place your raw CSV at `data_raw/user_orders-0.csv`.
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Launch Jupyter and open the notebook:
   ```bash
   cd project_x/notebooks
   jupyter notebook 01_data_cleaning.ipynb
   ```
4. Run all cells. The cleaned file will be written to `data_cleaned/user_orders_clean.csv` and a `cleaning_report.txt` will be created.

## Notes
- The notebook auto-detects the project root even if launched from `notebooks/` or the root.
- It will create missing folders and requires no manual path edits.
