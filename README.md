# Bank Term Deposit Prediction

Machine learning project using the UCI Bank Marketing dataset to predict whether a customer will subscribe to a term deposit.

## Models

- Logistic Regression
- Random Forest

## Workflow

- Data inspection and cleaning
- Exploratory data analysis
- Leakage-safe preprocessing
- Stratified train/test split
- Model training and comparison
- Accuracy, Precision, Recall, F1, ROC-AUC
- Confusion matrix and ROC curve
- Sample customer predictions
- Feature interpretation

The primary model excludes `contact`, `day`, `month`, `duration`, and `campaign`.

## Run

```bash
pip install pandas numpy seaborn matplotlib scikit-learn
```

Place `bank-full.csv` in the project directory and run the notebook cells sequentially.