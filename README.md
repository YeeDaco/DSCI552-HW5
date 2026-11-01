# DSCI 552 — Homework 5

Decision trees as interpretable models on the UCI Acute Inflammations data (label-powerset tree, IF-THEN rules, cost-complexity pruning), and regression on the UCI Communities and Crime data (imputation, correlation and coefficient-of-variation analysis, least squares, ridge, LASSO, PCR and an L1-penalized XGBoost model).

## Structure

```
.
├── README.md
├── .gitignore
├── data
│   ├── acute_inflammations
│   │   ├── diagnosis.data
│   │   └── diagnosis.names
│   └── communities_and_crime
│       ├── communities.data
│       └── communities.names
├── notebook
│   └── Lu_Yiming_HW5.ipynb
└── requirements.txt
```

## Run

```bash
pip install -r requirements.txt
cd notebook
jupyter notebook Lu_Yiming_HW5.ipynb   # then Kernel -> Restart & Run All
```

The notebook loads data with the relative paths `../data/acute_inflammations/` and `../data/communities_and_crime/`. `diagnosis.data` is UTF-16 encoded with tab separators and decimal commas; the notebook reads it accordingly.
