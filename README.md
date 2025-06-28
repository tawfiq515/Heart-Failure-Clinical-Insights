# Heart Failure Clinical Data Analysis ❤️📊

![Python](https://img.shields.io/badge/Python-3.11+-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-brightgreen)
![NumPy](https://img.shields.io/badge/NumPy-1.21+-orange)

A data analysis project exploring clinical features of 2,145 heart failure patients to identify risk patterns and statistical trends.

## Features
- **Statistical Analysis**: Mean, median, IQR, and standard deviation calculations for 50 clinical features.
- **Pattern Identification**: Top patients by blood pressure, glucose levels, and respiratory rate outliers.
- **Correlation Mapping**: Pearson correlation to find highly associated patient pairs.

## Installation
pip install numpy pandas


## Usage
Load the dataset:

import pandas as pd
df = pd.read_csv("HeartFailureDataset.csv")

Run analysis scripts (e.g., blood_pressure_analysis.py).

## Key Findings
Males showed lower mean heart rates (84.37 vs. 84.81).

"NT-proBNP" had the highest feature variability (IQR = 44,198).

Identified 53 patients with respiratory rates ±2σ from the mean.

## License
MIT


**Notes:**  
- Replace `HeartFailureDataset.csv` with your actual filename.  
- Adjust Python/Pandas/NumPy versions in badges if needed.  
- Add a `requirements.txt` if dependencies expand.  

