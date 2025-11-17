# recession_analysis

This repository contains a complete preprocessing workflow for four key U.S. macroeconomic indicators: GDP Growth, Unemployment Rate, Inflation Rate, and Recession Tags, sourced from World Bank WDI and FRED.
The project produces a fully cleaned, aligned, and merged dataset ready for exploratory data analysis, correlation studies, and machine learning.

project repository structure

recession_analysis/
│
├── cleansed data/
│   ├── processed_dataset.csv        # Final merged dataset (clean + aligned)
│   └── toS3                         # Placeholder for AWS S3 export
│
├── raw_data/
│   ├── GDP_USA.csv                  # GDP growth (annual %) from WDI
│   ├── USA_Inflation.csv            # Inflation (CPI) from WDI
│   ├── USA_Recession.csv            # Recession indicator (1/0) from FRED
│   ├── USA_Unemployment.csv         # Unemployment rate from FRED
│   └── desktop.ini
│
├── scripts/
│   └── Preprocessing.ipynb          # Full data-cleaning + merging pipeline
│
└── README.md


