# Credit Card Fraud Detection

This project uses XGBoost to detect fraudulent credit card transactions.

## Features
- Trained on Kaggle's Credit Card Fraud dataset
- Handles severe class imbalance with SMOTE
- Achieves ~98% ROC-AUC

## Files
creditcardfraud.ipynb  : Jupyter notebook with full pipeline
## Dataset Link
-https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
## 📸 Model Evaluation

Here’s the ROC curve showing high separability between fraud and non-fraud:

![ROC Curve](https://github.com/m-shashank2/CreditCardfraud_detection/raw/main/confusionmatrix.png)

And below is the confusion matrix after prediction:

![Confusion Matrix](images/confusion_matrix.png)

