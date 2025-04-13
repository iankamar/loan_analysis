# Loan Analysis Projects

This repository contains Jupyter notebooks for various loan-related machine learning projects.

## Projects

### Loan Acceptance Census Analysis
- **File**: `loan_acceptance_census_analysis.ipynb`
- **Description**: Predictive modeling to determine factors influencing loan approval decisions based on demographic data.
- **Techniques**: Feature engineering, correlation analysis, logistic regression
- **Outcomes**: Identified key approval indicators and improved decision transparency

### Loan Chargeoff Prediction
- **File**: `loan_chargeoff_prediction.ipynb`
- **Description**: Early warning system for potential loan defaults
- **Techniques**: Gradient boosting algorithms, financial behavior feature engineering
- **Outcomes**: Deployed model with custom risk thresholds to optimize collection strategies

## Setup and Requirements

### Dependencies
- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

### Installation
```bash
# Clone the repository
git clone https://github.com/iankamar/loan_analysis.git

# Navigate to the directory
cd loan_analysis

# Create a virtual environment (optional)
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate

# Install required packages
pip install -r requirements.txt

## License
Copyright © 2024 Ian Kamar. All rights reserved.