# Customer-Churn-Prediction

A machine learning project to predict whether a customer will churn or not based on their demographic and service usage data. This project includes exploratory data analysis, preprocessing, and multiple classification models to evaluate churn likelihood.

## 📊 Project Structure

- `Exploratory Data Analysis.ipynb`  
  Contains detailed analysis of customer churn dataset using visualizations and statistical summaries. Key steps include:
  - Understanding churn distribution
  - Feature-wise churn tendencies
  - Data cleaning and encoding
  - Correlation analysis

- `Model Building.ipynb`  
  Includes:
  - SMOTE oversampling to balance the dataset
  - Model building using Logistic Regression and Decision Tree
  - Hyperparameter tuning
  - Model evaluation using metrics like Accuracy, Precision, Recall, F1-Score, and Confusion Matrix

## 📁 Dataset Features

Some key features used for prediction:
- `Gender`, `Age`, `Tenure`
- `Internet Service`, `Tech Support`, `Contract Type`
- `Payment Method`, `Monthly Charges`, `Total Charges`
- `Churn` (Target variable)

## ⚙️ Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

## 🧠 Models Used

- Logistic Regression
- Decision Tree Classifier

## 🔍 Key Insights

- Certain features like Contract type and Tech Support have a strong relationship with churn.
- SMOTE helps in balancing the dataset and improves recall for minority class.
- Decision Trees provide better interpretability, while Logistic Regression offers better generalization.

## 🚀 How to Run

1. Clone this repo  
   ```bash
   git clone https://github.com/yourusername/customer-churn-prediction.git
   cd customer-churn-prediction

