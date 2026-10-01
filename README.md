# Predictive Analytics — DSC630

End-to-end predictive modeling pipeline demonstrating data preparation, feature engineering, model comparison, and decision-focused evaluation.

## Problem Statement
Build and compare predictive models for a real-world business outcome, evaluate trade-offs between accuracy and business cost, and deliver a reproducible workflow.

## Approach
- Data cleaning & feature engineering
- Exploratory Data Analysis
- Baseline + advanced models: Logistic Regression, Random Forest, XGBoost
- Evaluation: ROC-AUC, Precision-Recall, Confusion Matrix, Cost-sensitive threshold analysis
- Reproducible notebooks with clear narrative

## Tech Stack
Python • Pandas • Scikit-learn • XGBoost • Matplotlib/Seaborn • Jupyter • Streamlit

## Repo Structure
```
PredictiveAnalytics/
├─ notebooks/       # Weekly assignments & project notebooks
├─ data/            # Sample / processed data
├─ src/             # Reusable code
├─ reports/         # Figures & summaries
└─ app.py           # Streamlit demo
```

## Quick Start
```bash
pip install -r requirements.txt
jupyter lab notebooks/
streamlit run app.py
```

## Results
- Best model: XGBoost with ROC-AUC 0.89
- Optimal decision threshold tuned for business cost
- Dashboard prototype available via Streamlit

## License
MIT
