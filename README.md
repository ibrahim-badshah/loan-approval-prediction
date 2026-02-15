# Loan Approval Prediction System

A machine learning-based loan approval prediction system that compares multiple classification algorithms to determine loan eligibility. The system analyzes applicant data using Naive Bayes, Logistic Regression, and K-Nearest Neighbors (KNN) classifiers.

## 🎯 Project Overview

This project predicts whether a loan application should be approved or rejected based on various applicant features such as income, credit score, employment status, and more. The models are evaluated based on precision, recall, and accuracy metrics.

## 📊 Dataset Features

The dataset contains 1000 loan applications with the following features:

- **Personal Information**: Age, Gender, Marital Status, Dependents, Education Level
- **Financial Information**: Applicant Income, Co-applicant Income, Credit Score, Savings, Existing Loans
- **Loan Details**: Loan Amount, Loan Term, Loan Purpose, Collateral Value
- **Employment**: Employment Status, Employer Category
- **Other**: Property Area, Debt-to-Income (DTI) Ratio
- **Target Variable**: Loan_Approved (Yes/No)

## 🔧 Technologies Used

- Python 3.13
- Pandas & NumPy - Data manipulation
- Matplotlib & Seaborn - Data visualization
- Scikit-learn - Machine learning models and preprocessing

## 🚀 Models Implemented

| Model               | Accuracy | Precision | Recall |
|---------------------|----------|-----------|--------|
| Naive Bayes         |  86.5%   |   81.1%   |  70.4% |
| Logistic Regression |  86.5%   |   79.3%   |  75.4% |
| K-Nearest Neighbors |  77.5%   |   70.0%   |  45.9% |

**Best Model**: Naive Bayes (based on balanced precision performance for loan approval)

## 📁 Project Structure

```
loan-approval-prediction/
│
├── loan_approval_system.ipynb       # Main notebook with EDA and models
├── requirements.txt                 # Python dependencies
├── README.md                        # Project documentation
└── .gitignore                       # Git ignore file(Dataset)
```

## 📥 Installation & Setup

1. Clone the repository:
```bash
git clone https://github.com/ibrahim-badshah/loan-approval-prediction.git
cd loan-approval-prediction
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook:
```bash
jupyter notebook credit_wise_loan_system.ipynb
```

## 🔍 Key Findings

- Missing values handled using mean imputation for numerical features and mode imputation for categorical features
- Feature scaling applied using StandardScaler for optimal model performance
- Naive Bayes shows the best balance between precision and recall
- Credit Score, DTI Ratio, and Income are key predictors of loan approval

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 👤 Author

Ibrahim Badshah
- GitHub: https://github.com/ibrahim-badshah

