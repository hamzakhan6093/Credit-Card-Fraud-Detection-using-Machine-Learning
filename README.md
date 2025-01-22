# Credit-Card-Fraud-Detection-using-Machine-Learning


This repository contains a project aimed at detecting fraudulent credit card transactions using classification-based machine learning techniques. The project leverages Logistic Regression, Decision Tree, and Support Vector Machine (SVM) models to classify transactions as legitimate or fraudulent.

## Dataset

The dataset contains credit card transactions from European cardholders during September 2013. Features include:

- **V1-V28**: Anonymized numerical features representing various transaction attributes (e.g., location, type, etc.).
- **Amount**: The transaction amount.
- **Class**: Binary label indicating whether the transaction is fraudulent (1) or not (0).

The dataset is imbalanced, with fraudulent transactions representing a small fraction of all transactions.

---

## Project Steps

### 1. Importing Libraries
We start by importing the necessary Python libraries for data manipulation, visualization, and model building.

### 2. Loading the Dataset
The dataset is loaded into a Pandas DataFrame for processing.

### 3. Data Cleaning
Basic cleaning steps are performed to ensure data integrity:
- Checking for missing values.
- Handling duplicates if present.

### 4. Data Analysis
Exploratory data analysis (EDA) is conducted to understand the dataset:
- Distribution of the `Class` feature.
- Statistical summaries of transaction amounts.
- Visualizations of correlations among features.

### 5. Data Preprocessing
- Features are scaled to normalize the `Amount` feature and other numerical values.
- The dataset is split into features (`X`) and target (`Y`).

### 6. Splitting the Dataset
The dataset is split into training and testing sets.

### 7. Training the Models
Three models are trained on the dataset:
- Logistic Regression
- Decision Tree Classifier
- Support Vector Machine (SVM)

### 8. Evaluating the Models
The performance of each model is evaluated using accuracy, confusion matrix, and classification report.

### 9. Achieving High Accuracy
Through the above steps, the models achieve high accuracy, with the best-performing model achieving **99.85% accuracy** on the test set.

---

## Results
- The project demonstrates the effectiveness of classification models in detecting fraudulent transactions.
- Decision Tree and SVM models, in particular, provide excellent accuracy and robustness against imbalanced datasets.

---

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
```
2. Install the required libraries:
```bash
pip install -r requirements.txt
```
3. Run the Jupyter Notebook or Python script to execute the steps and train the models.

---

## Acknowledgments
This project uses the credit card fraud dataset made available by [Kaggle](https://www.kaggle.com).

