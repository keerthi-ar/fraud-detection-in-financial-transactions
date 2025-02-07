# Fraud Detection in Financial Transactions

## Objective:
The goal of this project is to identify fraudulent transactions in financial datasets, reducing financial losses for institutions. Using machine learning models, we aim to detect anomalies in transactions that may indicate fraudulent activity.

## Dataset:
This project uses the **Credit Card Fraud Detection Dataset** from Kaggle. The dataset contains credit card transaction details, where the target variable indicates whether the transaction was fraudulent (Class = 1) or not (Class = 0).

- **Dataset URL:** [Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

## Project Overview:
In this project, we build and evaluate machine learning models for detecting fraud in financial transactions. We explore and preprocess the dataset, handle class imbalance, and evaluate model performance using metrics like AUC-ROC and AUPRC. The following steps were taken:

### Steps Taken:
1. **Data Exploration and Preprocessing**:
   - Explored the dataset to understand class distribution and other statistical information.
   - Handled class imbalance using upsampling of the minority class.
   - Scaled the 'Amount' feature for model compatibility.
   - Split the dataset into training and testing sets.
   
2. **Model Building**:
   - Implemented and evaluated multiple anomaly detection models:
     - Isolation Forest
     - Autoencoder
   - Used models to predict fraudulent transactions and evaluate the performance.

3. **Evaluation**:
   - Evaluated the models using precision, recall, AUC-ROC, and AUPRC.
   - Plotted Precision-Recall Curves for better evaluation of imbalanced datasets.
   
4. **Model Interpretability**:
   - Used SHAP (SHapley Additive exPlanations) for model interpretability, highlighting key factors that influence fraud predictions.

5. **Feedback Loop**:
   - Designed a feedback loop to retrain the models on new fraud patterns and improve performance over time.

## Citation:
MLG-ULB. (2018). Credit Card Fraud Detection. Retrieved from https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud


## Installation:

To run this project on your local machine, you'll need to install the following libraries:

```bash
pip install shap
```
## Additional Dependencies:
This project was developed using Google Colab and requires the following libraries:
  - pandas
  - numpy
  - seaborn
  - matplotlib
  - scikit-learn
  - tensorflow

## Usage:

### Clone the repository:

```bash
git clone https://github.com/your-username/fraud-detection-in-financial-transactions.git
```


### Navigate to the project directory:

```bash
cd fraud-detection-in-financial-transactions
```

### Install the required libraries:

```bash
pip install -r requirements.txt
```

### Run the code:
```bash
python fraud-detection-in-financial-transactions.ipynb
```
