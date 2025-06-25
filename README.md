# Credit-Score-Classification-for-Paisabazaar
## 📝 Project Summary
This project aims to build a machine learning model to classify individuals' credit scores into categories — Poor, Standard, or Good — using financial and behavioral data. The model helps financial institutions like Paisabazaar make better lending decisions, reduce default risks, and personalize product recommendations.

## 📊 Business Context
Paisabazaar provides financial services, and assessing customer creditworthiness is central to risk management and loan approval. Accurate credit score classification enhances financial product offerings and reduces the chance of lending to risky customers.

## 🛠️ Project Workflow
- Data Exploration and Cleaning (EDA with Univariate, Bivariate, Multivariate Analysis)
- Feature Engineering & Preprocessing
- Handling Missing Values and Imbalanced Data
- Model Building (Logistic Regression, Random Forest, XGBoost)
- Hyperparameter Tuning and Cross-Validation
- SHAP-based Model Explainability

## 🧪 Models & Evaluation
We trained and evaluated multiple classification models:
- **Logistic Regression**
- **Random Forest Classifier**
- **XGBoost Classifier**

Evaluation metrics used:
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix

SHAP (SHapley Additive exPlanations) was used to interpret model outputs.

## 📈 Results
The XGBoost model delivered the highest accuracy and consistent results across all classes. Feature importance analysis revealed that factors like Annual Income, Outstanding Debt, and Credit Utilization Ratio significantly affect credit score classification.

## 🚀 How to Run
1. Clone this repository
```bash
git clone https://github.com/SuziSharma2/Credit-Score-Classification-for-Paisabazaar.git
cd Credit-Score-Classification-for-Paisabazaar
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Run the notebook
```bash
jupyter notebook Credit Score Classification for Paisabazaar.ipynb
```

## 📁 Project Structure
```
├── Credit Score Classification for Paisabazaar.ipynb     # Main notebook
├── data/                                  # dataset-2.csv
├── images/                                # Visualizations and SHAP plots
├── README.md                              # Project documentation
└── requirements.txt                       # Required libraries
```

## ✅ Requirements
- Python 3.7+
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- xgboost
- shap
- imbalanced-learn

## 👤 Author
Suzi Sharma
