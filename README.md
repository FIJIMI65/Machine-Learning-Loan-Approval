
# Loan Approval Prediction using Machine Learning

This project is a data science initiative to develop a predictive model that determines the likelihood of loan approval based on applicant demographics, financial attributes, and loan-specific features. It aims to assist microfinance institutions in making smarter, data-driven lending decisions, improving approval accuracy, reducing default risk, and promoting financial inclusion.

### Click here for more [![More Details badge](https://img.shields.io/badge/Click-Here-brightgreen.svg)](./Machine_Learning_Loan_Approval.ipynb)

## 🧠 Project Summary

Microfinance institutions face challenges in assessing loan applicants due to outdated processes. This project introduces a machine learning-based decision-support tool that predicts loan approval outcomes. By leveraging historical data and state-of-the-art algorithms, the model aims to:

- Reduce default rates by 15–30%
- Improve processing speed by 30–50%
- Increase loan approvals for creditworthy applicants
- Support operational scalability with modern ML systems

## 🧰 Tools & Technologies

- **Languages**: Python
- **Libraries**: pandas, scikit-learn, XGBoost, SHAP, matplotlib, seaborn
- **Framework**: CRISP-DM
- **Deployment**: Flask/FastAPI (REST API), Streamlit (dashboard), AWS/Azure (hosting)

## 🔍 CRISP-DM Phases Followed

1. **Business Understanding** – Defined the problem: predict likelihood of loan repayment and approval.
2. **Data Understanding** – Used a dataset of 58,645 loan records with 13 attributes.
3. **Data Preparation** – Applied cleaning, encoding, scaling, and feature engineering.
4. **Modeling** – Built and compared models: Logistic Regression, Decision Tree, Random Forest, XGBoost, Bagging, and Stacking.
5. **Evaluation** – XGBoost achieved 96% accuracy and 0.99 AUC-ROC.
6. **Deployment** – Planned REST API, web dashboard for loan officers, and batch prediction pipeline.

## 📊 Performance Highlights

- **Best Model**: XGBoost
- **Accuracy**: 96%
- **AUC-ROC**: 0.99
- **Precision/Recall**: ~96%
- **Explainability**: Feature importance via SHAP and ELI5

## 🛠️ Deployment Plan

- REST API for real-time predictions
- Web dashboard for loan officers (Streamlit/Dash)
- Batch processing pipeline for large-scale predictions
- Monitoring and feedback loop to retrain on new data

## ⚖️ Ethical & Fairness Considerations

- Performed bias checks across sensitive variables
- Integrated explainability tools for transparency
- Recommendations for fairness audits in production

## 📁 Project Structure

```
├── data/
│   └── loan_approval_prediction_train.csv
├── notebooks/
│   └── eda_and_modeling.ipynb
├── src/
│   ├── preprocessing.py
│   ├── model_training.py
│   └── api_service.py
├── app/
│   └── dashboard.py
├── reports/
│   └── Final_Report_Structured.docx
└── README.md
```

## 📌 Authors

- Arlie Cates
- Praise Ogbebor
- Eugenia Degbe
- Sai Venkata Sarada Niharika Penumalla

## 📜 References

CRISP-DM methodology, ML literature on loan approval, credit scoring, ensemble learning, SHAP explanations, model deployment strategies.

---

This project demonstrates the power of data science to support fair, scalable, and impactful lending practices. Contributions and feedback are welcome!
