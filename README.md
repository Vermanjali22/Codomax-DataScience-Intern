
# Customer Churn Prediction

**Codomax Digital Solution Virtual Internship — Final Data Science Project**

## Overview
This project analyzes telecom customer data and trains machine-learning classifiers to predict whether a customer may churn.

## Objectives
- Clean and explore customer data
- Visualize churn patterns
- Train Logistic Regression and Random Forest models
- Compare accuracy, precision, recall, F1-score, and ROC-AUC
- Summarize business implications and limitations

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Google Colab, GitHub.

## Run the project
1. Open `Customer_Churn_Prediction_Codomax.ipynb` in Google Colab.
2. Run all cells from top to bottom.
3. If the data URL does not work, download the CSV from the IBM sample-data repository and upload it to Colab. Set `DATA_PATH` in the data-loading cell to the uploaded file path.
4. Read the generated metrics and charts, then complete the conclusion with your actual results.

## Repository structure
```text
Customer-Churn-Prediction/
├── Customer_Churn_Prediction_Codomax.ipynb
├── README.md
├── requirements.txt
└── model_comparison_results.csv  # optional, generated after running notebook
```

## Evaluation
The notebook reports accuracy, precision, recall, F1-score, ROC-AUC, classification report, confusion matrix, and ROC curve. Metrics are generated at runtime; they are intentionally not hard-coded here.

## Limitations
The sample data may not reflect current customer populations. Model performance should be validated on fresh data and monitored before any real deployment. Feature importance is not evidence of causation.

## Author
Anjali Verma
