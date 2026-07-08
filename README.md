# Credit Risk Assessment

A machine learning project for loan default prediction built as part of the Business Analytics Certificate Program at IIT Mandi.

---

## What It Does

- Predicts loan default probability using real-world lending data
- Applies **statistical testing** to identify significant risk factors
- Engineers features to improve model signal quality
- Evaluates model performance using classification metrics
- Interprets results in a business decision-making context

## Models Used

| Model | Purpose |
|---|---|
| Logistic Regression | Baseline default probability estimation |
| Decision Tree | Interpretable rule-based classification |
| Random Forest | Ensemble method for improved accuracy |

## Performance Metrics

- Accuracy, Precision, Recall, F1-Score
- ROC-AUC curve for threshold-independent evaluation
- Confusion matrix for default vs non-default classification

## Key Risk Factors Analysed

- Debt-to-income ratio
- Credit history length
- Loan amount vs income
- Employment status
- Previous delinquencies

## Tech Stack

| Tool | Purpose |
|---|---|
| Python | Core logic |
| Pandas | Data cleaning and feature engineering |
| NumPy | Numerical operations |
| Scikit-learn | ML models and evaluation |
| Matplotlib / Seaborn | Visualizations |
| SciPy | Statistical testing |

## Key Concepts

- **Feature engineering** — creating meaningful predictors from raw data
- **Statistical hypothesis testing** — validating feature significance
- **Class imbalance handling** — addressing skewed default/non-default ratios
- **Model interpretability** — translating predictions into business decisions

## Project Structure

```
credit-risk-assessment/
│
├── credit_risk.py          # Main modeling pipeline
├── eda.py                  # Exploratory data analysis
├── feature_engineering.py  # Feature creation and selection
├── data/                   # Lending dataset
├── results/                # Model outputs and evaluation reports
└── README.md
```

## Usage

```python
# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn scipy

# Run model pipeline
python credit_risk.py
```

---

*Completed as part of IIT Mandi's Business Analytics Certificate Program. Focus on applying statistical rigor and ML methodology to real-world credit risk problems.*
