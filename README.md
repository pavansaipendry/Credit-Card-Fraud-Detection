# Credit-Card-Fraud-Detection

This project focuses on detecting fraudulent credit card transactions using machine learning, specifically the XGBoost classifier. The dataset consists of both legitimate and fraudulent transactions, and the aim is to build a model that can accurately classify these transactions.

### Project Overview
This repository includes the code for:

- Splitting the dataset into legitimate and fraudulent transactions.
- Using **XGBoost** to train a classifier that can handle class imbalance by adjusting the scale of positive weights.
- Evaluating model performance using various performance metrics.
- Dataset, is from kaggle. Access dataset from here https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

### Key Steps:
- **Data Preparation:** The dataset is split into fraudulent and legitimate transactions.
-  **Batch Processing:** Legitimate transactions are processed in batches to match the scale of fraudulent data.
- **Model Training**: XGBoost is used with class weight adjustments to account for class imbalance.
- **Evaluation**: The model is evaluated based on the classification report.

